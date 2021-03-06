## Shader Breakdown #1

By Rob Fichman aka bobacupcake, see [Shader Breakdown #1 | Rob Fichman on Patreon](https://www.patreon.com/posts/shader-breakdown-21471588)

Hi!! I've been meaning to write up some more official for my shaders, so I figured now was a good time to start! For this write-up I'm gonna be focusing on this friend and pal:

![1](1.gif)

A disclaimer for this one - it is pretty heavy on the GPU. A few of my shaders are meant for visual rather than in-game purposes, and are not optimized for real time (although I do want to optimize them at some point). With that aside, here's a rundown of what I'm doing!

The main wispy and sparkle effects are both done through raymarching through different types of 3d noise. (here are some good raymarching tutorials: [Ray Marching Metaball in Unity3D – Sehyun Av Kim – Medium](https://medium.com/@avseoul/ray-marching-metaball-in-unity3d-fc6f83766c5d) and [Volumetric Rendering - Alan Zucconi](https://www.alanzucconi.com/2016/07/01/volumetric-rendering/)). The sparkles are done through inverse 3d worley noise (potential trypophobia warning?),  which is generated by spreading feature points randomly in 3d space, and returning how close each point in space is to a feature point. While I put the regular worley noise value in the alpha channel, I assign each feature point a random color, and for each point in space I put the color of the nearest feature point into the rgb channel.

![1](1.png)

Then, in the shader, I use the alpha to determine the size of the sparkles (the closer to 1 the cutoff is, the smaller the sparkles will be), and I take the color and turn the rgb values into xyz values, giving me a direction for each sparkle (after subtracting 0.5 from each value to make sure all directions are accounted for). I use this to determine which sparkles to show based on view direction by taking the dot product of the view direction and the sparkle direction. Since the dot product of two directions facing eachother is -1, and the further away from facing eachother they get, the further away from -1 the dot product gets, I can use this to change the strength of each individual sparkle.

The wispy effect is a bit more hacked together: I started off with 3d perlin noise, and placed a bunch of random points in it. I then used the perlin noise as a pseudo-flow field, using the values of the perlin noise to determine what direction the points should move in, and storing their entire life cycle in another 3d texture. Here's a picture of some of my first tests with this, using just 2d space at first before I made the step up to 3d:

![1 1](1-1.png)

I then raymarched through this, and used a 2d noise texture as an offset, faked in 3d space (using the rgb channels of the 2d noise to offset the 3d noise in different directions) to really hone in the effect.

And lastly, I used a few other tricks to bring it all home - some gradients to change up the wisp and sparkle colors, double colored rim lighting based on what direction you view it from, and another 2d noise texture for some glass distortion.

![1 1](1-1.gif)

I hope this helped offer a bit of insight into my workflow!! Looking forward to writing some more tutorials like this when I get the time. Thank you for reading!!

![1 2](1-2.gif)