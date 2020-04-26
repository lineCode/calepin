- [Computer Science from the Bottom Up](https://www.bottomupcs.com/)
- [Channing Walton's answer to How do I explain to non-programmers how complex, time-consuming, and error-prone software development is? - Quora](https://www.quora.com/How-do-I-explain-to-non-programmers-how-complex-time-consuming-and-error-prone-software-development-is/answer/Channing-Walton-1)
- [Category Category](http://wiki.c2.com/?CategoryCategory) - Software Development & Programming General
- [Rosetta Code](http://rosettacode.org/wiki/Rosetta_Code)
- [xkcd: Good Code](https://xkcd.com/844/)

- [Simplified Wrapper and Interface Generator](http://www.swig.org/) connects programs written in C and C++ with a variety of high-level programming languages (Javascript, PHP, Python, C#, Java, etc.)
- [repl.it - Infinite Loops](https://repl.it/site/blog/infinite-loops) How to handle infinite loops in REPL
- [YourLanguageSucks - Theory.org Wiki](https://wiki.theory.org/YourLanguageSucks)
- [Wat Talks – Destroy All Software](https://www.destroyallsoftware.com/talks/wat) - Language strangeness. See [Wat — Destroy All Software Talks](Wat — Destroy All Software Talks.mp4)
- [Gamasutra - Dirty Coding Tricks](http://www.gamasutra.com/view/feature/4111/dirty_coding_tricks.php)
- [The Power of Ten – Rules for Developing Safety Critical Code](http://pixelscommander.com/wp-content/uploads/2014/12/P10.pdf)

![Bug Is A Feature](bug-is-a-feature.jpg)

## REPL

Aka Read–eval–print loop

- [codepad](http://codepad.org/) - Python, Ruby, Lua, C++, PHP, etc.
- [repl.it - Online REPL, Compiler & IDE](https://repl.it/) - Python, Ruby, C#, Java, C++, PHP, JS, etc.
- [PhpFiddle - PHP/MySQL in-browser IDE and online server](http://phpfiddle.org/) - PHP
- [Create a new fiddle - JSFiddle](https://jsfiddle.net/) - HTML, CSS, JS
- [JS Bin - Collaborative JavaScript Debugging](http://jsbin.com/) - HTML, CSS, JS
- [A Pen by Captain Anonymous](https://codepen.io/pen/) - HTML, CSS, JS
- [Online-REPs-and-REPLs](http://joel.franusic.com/Online-REPs-and-REPLs/) - list of online REPL
- [GLSL Sandbox Gallery](http://glslsandbox.com/) - Shader (GLSL)
- [RunKit + npm: {PACKAGE_NAME}](https://npm.runkit.com/{PACKAGE_NAME})
- [SQL Fiddle](http://sqlfiddle.com/)
- [C# Online Compiler | .NET Fiddle](https://dotnetfiddle.net/)

- [Read–eval–print loop — Wikipedia](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop)

## Things every developer should know

Aka prejudice and falsehoods about things

- [mr-mig/every-programmer-should-know: A collection of (mostly) technical things every software developer should know](https://github.com/mr-mig/every-programmer-should-know)
- [Curated list of falsehoods programmers believe in](https://github.com/kdeldycke/awesome-falsehood)
- [Things you should test: @noahsussman: Infinite Undo](http://infiniteundo.com/post/25230828820/things-you-should-test)
- [Falsehoods Programmers Believe About Names | Kalzumeus Software](http://www.kalzumeus.com/2010/06/17/falsehoods-programmers-believe-about-names/)
- [Falsehoods programmers believe about time: @noahsussman: Infinite Undo](http://infiniteundo.com/post/25326999628/falsehoods-programmers-believe-about-time)
- [Falsehoods programmers believe about addresses](https://www.mjt.me.uk/posts/falsehoods-programmers-believe-about-addresses/)
- [Falsehoods programmers believe about geography | Thias の blog](http://wiesmann.codiferes.net/wordpress/?p=15187&lang=en)

Due to cultural context

> En réalité, tout est biaisé ! Les algorithmes étant par essence des constructions humaines, les développeurs y implémentent leurs réalités culturelles, leur histoire, leur éducation… Le plus souvent de manière involontaire.
— [Cathy O'Neil - Les algorithmes comme construction sociale](https://rslnmag.fr/cite/algorithmes-constructions-sociales-lutter-biais-cathy-oneil/)

- [How and why the leap second affected Cloudflare DNS](https://blog.cloudflare.com/how-and-why-the-leap-second-affected-cloudflare-dns/#afalsehoodprogrammersbelieveabouttime)

Common preconception / belief

`rtt == 0` vs `rtt <= 0` make the difference. **Leave a comment why this particular condition is important.**

- [Curated list of falsehoods programmers believe in](https://github.com/kdeldycke/awesome-falsehood)
- [What I learned about languages just by looking at a Turkish typewriter – Medium](https://medium.com/@mwichary/what-i-learned-about-languages-just-by-looking-at-a-turkish-typewriter-fc840aab1b0a#)
- [What Every Programmer Absolutely, Positively Needs to Know About Encodings and Character Sets to Work With Text](http://kunststube.net/encoding/)
- [Numbers Every Programmer Should Know By Year](https://people.eecs.berkeley.edu/~rcs/research/interactive_latency.html)
- [One second code: Do YOU know how much your computer can do in a second?](http://computers-are-fast.github.io/)

See also:

- [Person](../Data/Person.md)
- [Date & Time](../Data/Date%20&%20Time.md)
- [Postal address](../Data/Postal%20address.md)

## Development skill

1. Can I do this?
2. Can I do this more easily?
3. Can I do this more elegantly?
4. Can I not do this?

## Reasons why code breaks

> QA Engineer walks into a bar. Orders a beer. Orders 0 beers. Orders 999999999 beers. Orders a lizard. Orders -1 beers. Orders a sfdeljknesv.

- code is untested: back your code with **automated tests**!
- code does not report errors: use **exception reporting** mechanisms like services that collect live crash reports
- code remains isolated too long: integrate often! Make **continuous integration** part of your development workflow.
- code is developed in isolation: consider **pair programming** and/or regular **code reviews** to share "code ownership".
- code solves problems that aren't there: make sure you **don't overengineer**. Keep things as simple as possible.
- code reinvents the wheel: keep your eyes open for good **third-party libraries** that have stood the test in other projects already.
- code depends on too many external pieces: use **third-party libraries** only when you're convinced that they are of high quality - and you really need them.
- code is not actively maintained: schedule time for regular **refactorings**.

> Arriving at stable, secure code is mostly a question of discipline. Professional tools and workflows can help a lot in avoiding the most common problems (and catastrophes).

- [8 Reasons Why Code Breaks](https://www.git-tower.com/blog/reasons-why-code-breaks/)

### Mysterous reasons

- [You can't enter text in the body of email messages in Outlook on the web in Internet Explorer](https://support.microsoft.com/en-us/kb/2935743) - You can't type emails. It might be the antivirus, needed to be disabled.
- [Software Folklore ― Andreas Zwinkau](http://beza1e1.tuxen.de/lore/)
- [The Order of the JSON – Dion Almaer](https://blog.almaer.com/the-order-of-the-json/) - JSON keys almost cost a project millions of dollars and months of time

## Logging

Syslog Severity Levels (importance or severity, from high to low):

- Emergency (0) aka panic, emerg: "Your application is completely broken. If you sleep, you must wake up and begin to repair your application.". Ex: crashes, stopped processes
- Alert (1): "Your application does not work. If you going to go to bed, you should not do it, you must begin to repair your application.". Ex: platform errors
- Critical (2) aka crit: "Your application is running, but can be broken soon. If you eat, you should do it quickly and begin to repair your application.". Ex: hardware issues, port security, STP
- Error (3), aka err: "Your application is running, but something bad happened. You must add the task "fix the bug" to your to-do list.". Ex: ACL issues, TCAM issues, PAgP problems, ethernet controller, interface up/down
- Warning (4), aka warn: "Your application is running, but soon you may see error messages. You should add the task "fix the bug" to your to-do list.". Ex: DHCP snooping
- Notifications (5) aka notice: "Your application is running, but something unusual happened. You have to think about it in your spare time.". Ex: 802.1X, DTP, EtherChannel, inline power, STP, interface line protocol
- Information (6), aka info: "Your application works fine. These messages show how well.". Ex: stack events, port security, dynamic ARP inspection, VTP, UDLD, STP, hardware diagnostics
- Debug (7): "You can use it during development. And do not use in production environment.". Ex: debug output

Note: Unless compliance demands it, levels 5, 6 and 7 are not required and will consume unnecessary resources.

- [syslog - Wikipedia](https://en.wikipedia.org/wiki/Syslog#Severity_level)
- [System Message Logging - Cisco](https://www.cisco.com/c/en/us/td/docs/routers/access/wireless/software/guide/SysMsgLogging.html#wp1054858)
- [Syslog severity levels](https://support.solarwinds.com/SuccessCenter/s/article/Syslog-Severity-levels)

## Technical dept

> ## Non breacking release of Webpack 4
> 
> - **4.0.0**, 4.0.1, **4.1.0**, 4.1.1, **4.2.0**, **4.3.0**, **4.4.0**, 4.4.1, [...]
> - 33 **minor** releases
> - 43 patch releases
> - but: **technical debt** pills up...
> 
> ## Strategy to prevent major releases
> 
> - hacks, and add **TODOs** to the source code
> - opt-in flags
> - **plan** ahead of **future features**
> 	- make necessary **preparations** in major releases
> - restrict API to be able to do changes in **non-breacking way**
> 	- very difficult, because of the **large plugin API surface**
> 
> — [slides/webpack-5-why-breaking-changes.pdf at master · sokra/slides](https://github.com/sokra/slides/blob/master/data/webpack-5-why-breaking-changes.pdf)

## Latency numbers

- [The Infinite Space Between Words](https://blog.codinghorror.com/the-infinite-space-between-words/)
- [Numbers Every Programmer Should Know By Year](https://people.eecs.berkeley.edu/~rcs/research/interactive_latency.html)
- [Numbers Every Programmer Should Know By Year](https://people.eecs.berkeley.edu/%7Ercs/research/interactive_latency.html)

## Multiple users

Aka multiplayer game, streaming, RTS game

- [How Figma’s multiplayer technology works](https://www.figma.com/blog/how-figmas-multiplayer-technology-works/)
- [Gamasutra - 1500 Archers on a 28.8: Network Programming in Age of Empires and Beyond](http://www.gamasutra.com/view/feature/131503/1500_archers_on_a_288_network_.php)
- [Gamasutra - Opinion: Synchronous RTS Engines And A Tale of Desyncs](http://www.gamasutra.com/view/news/126022/Opinion_Synchronous_RTS_Engines_And_A_Tale_of_Desyncs.php)
- [A Beginner's Guide to Scaling to 11 Million+ Users on Amazon's AWS - High Scalability -](http://highscalability.com/blog/2016/1/11/a-beginners-guide-to-scaling-to-11-million-users-on-amazons.html) http://wayback.archive.org/web/20160304044912/http://highscalability.com/blog/2016/1/11/a-beginners-guide-to-scaling-to-11-million-users-on-amazons.html
- [Lag compensation techniques for multiplayer games in realtime | Gamedonia](http://www.gamedonia.com/blog/lag-compensation-techniques-for-multiplayer-games-in-realtime)
- [Source Multiplayer Networking - Valve Developer Community](https://developer.valvesoftware.com/wiki/Source_Multiplayer_Networking)
- [Gaffer on Games | Glenn Fiedler's Game Development Articles](http://gafferongames.com/)
- [RedpointGames/netcode.io-browser: Browser extensions which enable the use of netcode.io (secure UDP) prior to adoption in web browsers](https://github.com/RedpointGames/netcode.io-browser)

## Complexity

> The more things you have to special case, the worse your code is
— [Lea Verou](https://twitter.com/LeaVerou/status/816271623619825664)

Magic = complexity. With react, JSX is magic

- [Pourquoi les développeurs détestent-ils le low-code ? - Le Monde Informatique](https://www.lemondeinformatique.fr/actualites/lire-pourquoi-les-developpeurs-detestent-ils-le-low-code-76497.html)
- [Le monde du logiciel est en train de se détruire... Manifeste pour un développement plus durable - GREENSPECTOR®](https://greenspector.com/fr/articles/2018-12-11-manifeste-developpement-plus-durable/)

## The wrong way

Often due to [complexity](#complexity) or [misconceptions and falsehoods](#falsehoods)

> Apparently, when they didn't have the right data for a vehicle, a privately operated citation processing center used the word NULL in the license plate field for many tickets. Since that just happens to be Droogie's license plate, he got all of them. 
> Droogie contacted the DMV who told him to change his plate. He refused because he didn't do anything wrong. While they wiped the fines off his record, unfortunately for him, they didn't fix the problem in the system so once again, Droogie has accrued another $6,000 in tickets that he had nothing to do with. He says he won't be paying those either. 
> 
> — [!FALSE 😜 on Twitter: "Vanity license plate "NULL" goes horribly wrong https://t.co/yyz13fyODV via @JohnMu https://t.co/okznfwSQhV" / Twitter](https://twitter.com/mahemoff/status/1160989395043934208?s=12)

- [The Daily WTF: Curious Perversions in Information Technology](http://thedailywtf.com/)
- [The Inner JSON Effect - The Daily WTF](http://thedailywtf.com/articles/the-inner-json-effect) A story about some weird enterprise framework "JDSL" using SVN revisions to do store code fragments, and reference it later by the revision ID.
- [Project from Hell | Project Failures](https://projectfailures.wordpress.com/2008/06/24/project-from-hell/)
- [How To Write Unmaintainable Code](https://github.com/Droogans/unmaintainable-code)
- [Pourquoi réécrire un projet en partant de zéro ? Parce que l'ancien code est un fatra ou qu'il est plu facile d'écrire que de lire un code ?](https://www.developpez.com/actu/200958/Pourquoi-reecrire-un-projet-en-partant-de-zero-Parce-que-l-ancien-code-est-un-fatras-ou-qu-il-est-plus-facile-d-ecrire-que-de-lire-un-code/)
- [Thing You Should Never Do, Part I – Joel on Software](https://www.joelonsoftware.com/2000/04/06/things-you-should-never-do-part-i/)

## Performance and optimization

- [Category Optimization](http://wiki.c2.com/?CategoryOptimization) - range of subjects related to performance

See also [Multiple users](#multiple-users)

### Premature optimization

**Don't, unless you know what you are doing (your are an expert)**

Could kill optimization.
If so **add comments** to explain the choice.

- [The Fallacy of Premature Optimization](http://ubiquity.acm.org/article.cfm?id=1513451)

## Feature flag

- [To cut down on bugs, Apple is changing how it develops its software | Ars Technica](https://arstechnica.com/gadgets/2019/11/to-cut-down-on-bugs-apple-is-changing-how-it-develops-its-software/)
- [Feature Policy | WebKit](https://webkit.org/feature-policy/)
- [ExposureGuidelines - MozillaWiki](https://wiki.mozilla.org/ExposureGuidelines)
- [Adding a new feature flag in chrome://flags](https://chromium.googlesource.com/chromium/src.git/+/master/docs/how_to_add_your_feature_flag.md)

## Localization

See [Localization](../Conception/Conception.md#localization), [Locale](../Data/Locale/Locale.md)

- [A Programmer’s Introduction to Unicode – Nathan Reed’s coding blog](http://reedbeta.com/blog/programmers-intro-to-unicode/)
- [UTF-8](UTF-8)
- [Unicode](Unicode)

### Pseudo locale

Fake langues to test UI, etc.

- [Staś Małolepszy: Pseudolocales for Firefox OS](http://informationisart.com/27/)
- [Pseudo-Locales (Windows)](https://msdn.microsoft.com/en-us/library/windows/desktop/dd319106%28v=vs.85%29.aspx)
- [Using Pseudo-Locales for Localization Testing (Windows)](https://msdn.microsoft.com/en-us/library/windows/desktop/dd374118%28v=vs.85%29.aspx)
- https://github.com/mozilla-b2g/gaia/blob/75bf3cbf589a01d735ebf8653732b721627c8701/build/l10n.js#L24-L128 and https://github.com/mozilla-b2g/gaia/blob/19e6df7cc6111c9d6f8150f8191f0d2d8e76004d/shared/js/l10n.js#L1036-L1146

### Libs and tools

- International Components for Unicode (ICU) libraries - use CLDR data for most data. Additional data for conversion data and break iterator
	- [ICU User Guide](http://userguide.icu-project.org/)
	- [Formatting Messages - ICU User Guide](http://userguide.icu-project.org/formatparse/messages)
	- [ICU Data - ICU User Guide](http://userguide.icu-project.org/icudata)
	- [ICU Demonstration - Explorateur de locales d'ICU](http://demo.icu-project.org/icu-bin/locexp)
- gettext
	- [gettext — Wikipedia](https://en.wikipedia.org/wiki/Gettext)
	- [gettext - GNU Project - Free Software Foundation (FSF)](https://www.gnu.org/software/gettext/gettext.html)
	- [internationalization - Internationalising sentences with two plural words - Stack Overflow](https://stackoverflow.com/questions/1888487/internationalising-sentences-with-two-plural-words)
	- [Gettext i18n utility for Javascript; GNU JS Gettext](https://github.com/adrienrn/jsgettext) - Javascript implemenation of GNU Gettext API
	- [PHP: Gettext - Manual](http://php.net/manual/en/book.gettext.php)
	- [PHP: ngettext - Manual](http://php.net/manual/en/function.ngettext.php) - Plural version of gettext
- webL10n - Localization lib support pluralization
	- [Client-side internationalization / localization library](https://github.com/fabi1cazenave/webL10n)
	- [Localizing Firefox OS Apps ★ Mozilla Hacks – the Web developer blog](https://hacks.mozilla.org/2013/08/localizing-firefox-os-apps/)
	- [L20n - MozillaWiki](https://wiki.mozilla.org/L20n)
- Globalize.js - use CLDR data
	[A JavaScript library for internationalization and localization](https://github.com/globalizejs/globalize)
- L10ns - JavaScript Internationalization workflow and formatting. Use ICU's message format (based mostly on CLDR data)
	- [L10ns](http://l10ns.org/)
	- [L10ns - Effective translation workflow](https://github.com/tinganho/l10ns)
	- [Pluralization for JavaScript · An A List Apart Article](https://alistapart.com/article/pluralization-for-javascript)
	
	See also
	- [Client-side internationalization / localization library](https://github.com/fabi1cazenave/webL10n)
	- [RootsLabs » Firefox OS : Localiser son application](https://rootslabs.net/blog/184-firefox-os-localiser-son-application)
- messageformat.js - Gender and plural-capable messages using ICU MessageFormat (based mostly on CLDR data)
	- [messageformat.js · ICU MessageFormat for Javascript](https://messageformat.github.io/)
	- [messageformat/messageformat: ICU MessageFormat for Javascript - i18n Plural and Gender Capable Messages](https://github.com/messageformat/messageformat)
- LocalePlanet - Javascript, use ICU
	- [LocalePlanet: L10N et I18N pour JavaScript](http://www.localeplanet.com/index.html)
	- [LocalePlanet Translation Tools](http://www.localeplanet.com/support/tools.html) and [LocalePlanet tools](https://github.com/fileformat/lptools)
- ECMAScript Internationalization API, which provides language sensitive string comparison, number formatting, and date and time formatting. Missing MessageFormat
	ECMA-402 API
	- [Standard ECMA-402](http://ecma-international.org/publications/standards/Ecma-402.htm)
	- [Intl - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl)
	- [ECMA-402 JavaScript Internationalization API "shim"](https://github.com/ibm-js/ecma402) - Polyfill use CLDR data
	- [Compatibility implementation of the ECMAScript Internationalization API](https://github.com/andyearnshaw/Intl.js)
	- [Introducing the JavaScript Internationalization API ★ Mozilla Hacks – the Web developer blog](https://hacks.mozilla.org/2014/12/introducing-the-javascript-internationalization-api/)
- Intl MessageFormat - Format a string with placeholders, including plural and select support to create localized messages
	Use ICU Message syntax, CLDR data and ECMA-402 API
	- [Intl MessageFormat](https://github.com/yahoo/intl-messageformat)
	- [FormatJS](https://formatjs.io/)
- PHP Locale
	- [PHP: Locale - Manual](http://php.net/manual/en/class.locale.php)
	- [PHP: Locale::parseLocale - Manual](http://php.net/manual/en/locale.parselocale.php)
	- [PHP: ResourceBundle - Manual](http://php.net/manual/en/class.resourcebundle.php)
- PHP Zend Framework internationalization component - plural translations and text domains. The fallback to a default locale use Intl PHP extension
	- [I18n component from Zend Framework](https://github.com/zendframework/zend-i18n)
- [Locale | Android Developers](https://developer.android.com/reference/java/util/Locale.html)
- [NSLocale - NSHipster](http://nshipster.com/nslocale/)
- [MessageFormat (Java Platform SE 7 )](http://docs.oracle.com/javase/7/docs/api/java/text/MessageFormat.html) (`java.text.MessageFormat` replace `com.ibm.icu.text.MessageFormat`)
- https://dxr.mozilla.org/mozilla-central/source/intl/locale/PluralForm.jsm - see [Localization and Plurals - Mozilla | MDN](https://developer.mozilla.org/en-US/docs/Mozilla/Localization/Localization_and_Plurals)
- [Easy localization for Rails apps | Locale](https://www.localeapp.com/)
- [Localization tools with Python API for building localization & translation systems](https://github.com/translate/translate)
- [Moment.js | Home](http://momentjs.com/)
- [Numeral.js](http://numeraljs.com/)
- [A super simple currency formatting library](https://github.com/osrec/currencyFormatter.js)

Notes:

- Google Translate: `iw` to `he`
- ICU: underscores to dashes, `nn` to `no`, extraneous script removed if non-script version doesn't exist. 
- Java: underscores to dashes, reorder script to be at the end, `iw` to `he`, `in` to `id`, `hi` has no language-only variant, only `hi-IN`
- ICU, Java and .Net don't use exact same locale IDs [Complete List](http://www.localeplanet.com/compare/all.html). See also [Compare Locale Data Sources](http://www.localeplanet.com/compare/index.html)

## Snippet

- [Programming Idioms](https://www.programming-idioms.org/)

## Slugify

Normalize first ("NFD"), remove all non A-Za-z chars

- [slugify/Resources/rules at master · cocur/slugify](https://github.com/cocur/slugify/tree/master/Resources/rules)
- [String.prototype.normalize() - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/normalize)

## Naming

Aka naming things, few words

> There are only two hard things in Computer Science: cache invalidation and naming things.
— Phil Karlton

- [Is naming things really that hard?](http://wade.be/development/2017/03/03/naming-things.html)
- [Naming Things | DevIQ](http://deviq.com/naming-things/)
- [Naming Guidelines](https://msdn.microsoft.com/en-us/library/ms229002%28v=vs.110%29.aspx)
- [Sensible Interfaces](http://verraes.net/2013/09/sensible-interfaces/)
- [Rob Pike: Notes on Programming in C](https://www.lysator.liu.se/c/pikestyle.html)

> Local variables
> 
> Keep them short; long names obscure what the code does.
> 
> Common variable/type combinations may use really short names: 
> Prefer i to index.
> Prefer r to reader.
> Prefer b to buffer.
> Avoid redundant names, given their context:
> 
> Prefer count to runeCount inside a function named RuneCount.
> Prefer ok to keyInMap in the statement 
> [...]
> Longer names may help in long functions, or functions with many local variables.
> (But often this just means you should refactor.) 
> 
> — [What's in a name?](https://talks.golang.org/2014/names.slide#6)

> Junior devs, variable naming is SO important.
> 
> I'm working with one of my mentees right now and I can clearly see why she's getting confused. The variable names are not representative (enough) of what they are holding.
> 
> When I had her rename all of her variables, she excelled.
> 
> — [Angie Jones on Twitter: "Junior devs, variable naming is SO important. I'm working with one of my mentees right now and I can clearly see why she's getting confused. The variable names are not representative (enough) of what they are holding. When I had her rename all of her variables, she excelled." / Twitter](https://twitter.com/techgirl1908/status/1247344099801227265)

See also [Case styles](#case-styles)

- [Glue code — Wikipedia](https://en.wikipedia.org/wiki/Glue_code)
- Patch: a piece of tape covering some punched holes [Patch (computing) — Wikipedia](https://en.wikipedia.org/wiki/Patch_%28computing%29)
- [Software bug — Wikipedia](https://en.wikipedia.org/wiki/Software_bug)
- Mangle [Name mangling — Wikipedia](https://en.wikipedia.org/wiki/Name_mangling)
- threshold (seuil)
- leading (heading), trailing (tail, rear)
- header, trailer
- tight, thin, narrow vs wide, large, thick
- lead, base
- setting
- [payload](https://en.wikipedia.org/wiki/Payload_%28computing%29) (network)
- analytics / a7s
- source / src, destination / dst / dest
- constructor / ctor
- watermark / fingerprint / hash
- stale (original state)
- dry run (testing process) https://en.wikipedia.org/wiki/Dry_run_(testing)
- noop / No Operation
- canonical
- prefix, suffix
- behaviour
- computation
- tulpe "a data structure consisting of multiple parts. (in a relational database) an ordered set of data constituting a record." See also destructuring
- nonempty ["Not empty" set in one word? - English Language & Usage Stack Exchange](https://english.stackexchange.com/questions/102771/not-empty-set-in-one-word)
- edges (endpoints) and fields
- substitute something (ex: `substituteTLDHost("example.com") // -> "example"`)
- normalized / mung / hash / slug (remove non ASCII chars, remove accents, purged data) [Mung (computer term) — Wikipedia](https://en.wikipedia.org/wiki/Mung_%28computer_term%29)
- user, admin/administator, standard user,  [nonadministrator](https://en.wiktionary.org/wiki/nonadministrator) / non-administrator user / unprivileged users, member, registered user
	editors, authors / writers, proofreaders / copywriters / correctors, commenters, translators, illustrators / photographers, designers, programmers / coders, supporters, contributors, uploaders / seeders, downloaders / leechers and readers / viewers / listeners
	members, staff, public, consumers, trustees, board, humans / people, machines / bots / crawlers
	
	[web app - What is a good name for non-administrator users
	? - User Experience Stack Exchange](http://ux.stackexchange.com/questions/27769/what-is-a-good-name-for-non-administrator-users)
- greatest distance, longest path, high score
- concurrency, race condition
- [tuple](https://en.wikipedia.org/wiki/Tuple): finite ordered list
- [Deterministic algorithm — Wikipedia](https://en.wikipedia.org/wiki/Deterministic_algorithm)
- credentials - [Username + password = one word - English Language & Usage Stack Exchange](https://english.stackexchange.com/questions/309008/username-password-one-word)
- authentication [nouns - Is "authentification" a real word? - English Language & Usage Stack Exchange](https://english.stackexchange.com/questions/7844/is-authentification-a-real-word)
	
- [Glossary](http://catb.org/jargon/html/go01.html)
- [Find Similar or Opposite words at WordHippo](http://www.wordhippo.com/)

> \#python tip: Avoid property() setters when the effect of the setting isn't obvious:
> 
> 	bill.price = 1.15
> 	bill.quantity = 20
> 	bill.total = 19.50  # What changes, the price or quantity?
> 
> Better:
> 
> 	bill.adjust_price_giving_total(19.50)
> [...]
> 
> 	t = Temperature(celsius=17)
> 	t.fahrenheit *= 1.10  # updates the celsius attribute
> 	print(t.celsius)          # regular attribute
> 	print(t.farhenheit)    # computed field
> 
> [...]
> 
> Solution:  Make the computed field read-only and move the update feature to a well-named method.

> don't try and name a function by looking at its implementation as you'll only come up with a name that reflects how it works. Instead look at the call sites and see what they want to know or do.
> — [Chris Oldwood](https://twitter.com/chrisoldwood/status/1026914381613985792)

> Alternatives for get: create, build, make, acquire, allocate, find, locate, fetch, request, retrieve, pull, derive, calculate, format, ...
> — [Chris Oldwood](https://twitter.com/chrisoldwood/status/693398223705260033)
See also read, inspect,...

> There are only two hard things in Computer Science: cache invalidation and naming things.
> — Phil Karlton

> - use meaningful function names
> - describe **what** it does, **not how** it does it
> - i.e. do not expose the implementation details in the name

Use more appropriate terms. Exemple, instead of "master and slave", use "primary and secondary" or "initiator and responder" (based on the context). For "whitelist and blacklist", use "safelist" and "blocklist".

- [Paul Vixie sur Twitter : "as the originator of the terms, i have to say, "master and slave" describe protocol roles not data mod](https://mobile.twitter.com/paulvixie/status/942849555111874560)
- [Kelly Ellis sur Twitter : "The notion that the terms "master" and "slave" have no historical context is false. Otherwise they wo](https://mobile.twitter.com/justkelly_ok/status/933460605813641216)
- [Amy Gebhardt on Twitter: "Huh! Just noticed that @travisci doesn't use whitelist/blacklist terminology. Instead, they choose "safelist" and "blocklist" in their documentation 💯 There. Now you have alternatives too. Let's stop using problematic phrases, yeah? Language matters. And it's not that hard." / Twitter](https://twitter.com/amlyhamm/status/1202684742069604353)

See [synonymicon](https://en.wiktionary.org/wiki/synonymicon) / thesaurus

- [Naming is a process, not a single step « Arlo Being Bloody Stupid](http://arlobelshee.com/good-naming-is-a-process-not-a-single-step/) - Blog posts serie

### Naming convention

Aka case style, casing

- [`camelCase` `PascalCase`](https://en.wikipedia.org/wiki/Camel_case)
- [`underscore_case` (`snake_case`)](https://en.wikipedia.org/wiki/Snake_case)
- [`hyphen-case` (`kebab-case`)](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles)
- [`StUdLyCaPs`](https://en.wikipedia.org/wiki/Studly_caps)
- [`Capitalize`](https://en.wikipedia.org/wiki/Capitalization) (CSS, uppercase first letters of all words): "February 4th, 2015" (not "February 4Th, 2015")
- [`Title Case`](https://en.wikipedia.org/wiki/Letter_case#Initial-caps) (used in titles of books, movies, songs, and poems, where articles are lowercase). ex: "Raiders of the Lost Ark". See https://github.com/gouch/to-title-case (for english only)
- [`caps-for-acronyms`](https://en.wikipedia.org/wiki/Acronym#Small-caps_variant)

- [Naming convention (programming) — Wikipedia](https://en.wikipedia.org/wiki/Naming_convention_%28programming%29#Multiple-word_identifiers)
- [Letter case — Wikipedia](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles)
- [Naming convention for multi-word identifiers with initialisms](https://esdiscuss.org/topic/naming-convention-for-multi-word-identifiers-with-initialisms)

## Write readable code

See also [complexity](#complexity).

> It’s harder to read code than to write it.
> — Joel Spolsky

> when you start from scratch there is **absolutely no reason** to believe that you are going to do a better job than you did the first time
> — Joel Spolsky

> Writing code that others will read (including your future self) is about making yourself easy to understand.
> 
> It's not about:
> - being clever
> - showing how much you know
> - using this new thing you just learned about
> - typing the fewest characters possible
> 
> — [Brian Hilson on Twitter: "Writing code that others will read (including your future self) is about making yourself easy to understand. It's not about: - being clever - showing how much you know - using this new thing you just learned about - typing the fewest characters possible https://t.co/ythAeaw1XJ" / Twitter](https://twitter.com/brianhilson/status/1220296329517322240?s=12)

### Comments

> The proper use of comments is to compensate for our failure to express ourselves in code.
> 
> — Robert C. Martin

> Every comment represents a failure to make the code self explanatory
> 
> — Robert C. Martin

	// Check to see if the employee is eligible for full benefits
	if ((employee.flags & HOURLY_FLAG) && (employee.age > 65)) {
		…
	}

vs.:

	if (employee.isEligibleForFullBenefits()) {
		…
	}

> Much of the time, a comment can be improved by deleting it and encapsulating meaning in well-named functions or variables

Comments should complement the code. Maybe add notes on how to test, where the stubs are, dependencies...tacit knowledge beyond the code

> Code comments document the why, not the how
> [...]
> Documentation is for every possible user
> [...]
> Saying that variable names are the only documentation needed means that only people who read your code can use it
> 
> — [“My Code is Self-Documenting” — Eric Holscher - Surfing in Kansas](http://ericholscher.com/blog/2017/jan/27/code-is-self-documenting/)

- [Code Tells You How, Comments Tell You Why](https://blog.codinghorror.com/code-tells-you-how-comments-tell-you-why/)
- [Thoughts on Self-Documenting CSS](http://keithjgrant.com/posts/2017/06/self-documenting-css/)
- [La notion de code source autodescriptif relèverait d'un mythe entretenu par les programmeurs qui n'ont pas saisi la portée de « documenter »](https://www.developpez.com/actu/150976/La-notion-de-code-source-autodescriptif-releverait-d-un-mythe-entretenu-par-les-programmeurs-qui-n-ont-pas-saisi-la-portee-de-documenter/)

## Code quality

Time spend vs quality / technical debt

Organization complexity is predictor of bugs (more preople + more departments + higer turnover = worse code): [The Influence of Organizational Structure On Software Quality: An Empirical Case Study - Microsoft Research](https://www.microsoft.com/en-us/research/publication/the-influence-of-organizational-structure-on-software-quality-an-empirical-case-study/)

### Testing

Domain-Driven Design : on étudie le problème en large et en travers avant de concevoir et avant de programmer

- [unit testing](https://en.wikipedia.org/wiki/Unit_testing) (individual module testing) + [integration testing](https://en.wikipedia.org/wiki/Integration_testing) (test modules all together)
- [Code smell](https://en.wikipedia.org/wiki/Code_smell)
- [Technical debt](https://en.wikipedia.org/wiki/Technical_debt)
- [Slow Is Fast](http://www.programmerfu.com/2017/04/20/fast-is-slow-slow-is-smooth-smooth-is-fast.html) - [Trolldi : pourquoi coder lentement c'est coder plus vite, mais aucun développeur ne peut le faire dans la réalité](https://www.developpez.com/actu/144428/Trolldi-pourquoi-coder-lentement-c-est-coder-plus-vite-mais-aucun-developpeur-ne-peut-le-faire-dans-la-realite/)

### Linting and static analyzing

- JavaScript/ECMAScript:
	- ESLint
	- JSLint
	- JSHint
	- [SonarLint](https://www.sonarlint.org/)
	- [Standard JS](https://github.com/standard/standard)
	- [PMD](https://github.com/pmd/pmd)
- CSS:
	- CSS Lint
	- Stylelint (compatible with LESS and SASS)
- Shell scripts:
	- [ShellCheck](https://github.com/koalaman/shellcheck)
- Docker files:
	- hadolint
- Ruby:
	- Rubocop
	- [SonarLint](https://www.sonarlint.org/)
- PHP:
	- [php-cs-fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
	- [phpstan](https://github.com/phpstan/phpstan)
	- [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)
	- [SonarLint](https://www.sonarlint.org/)
	
	See also [Is there a static code analyzer \[like Lint\] for PHP files? - Stack Overflow](https://stackoverflow.com/questions/378959/is-there-a-static-code-analyzer-like-lint-for-php-files/379471#379471)
- TypeScript:
	- TSLint
- Python:
	- Flake8
	- Black
	- [pylint](https://github.com/PyCQA/pylint)
	- Pylama
	- [SonarLint](https://www.sonarlint.org/)
- HTML:
	- HtmlHint
	- [selective lint](https://github.com/ChristianMurphy/selective)
	- [rehype parse errors](https://github.com/rehypejs/rehype/tree/master/packages/rehype-parse#optionsemitparseerrors)
	- [SonarLint](https://www.sonarlint.org/)

	See also linter for website/webpage
	See also [globant-ui/arialinter](https://github.com/globant-ui/arialinter) (accessibility) and [DuaneOBrien/A11YLint-Brackets](https://github.com/DuaneOBrien/A11YLint-Brackets) (accessibility)
	[Linter based on rehype · Issue #1 · rehypejs/ideas](https://github.com/rehypejs/ideas/issues/1)
- Markdown/CommonMark:
	- Markdownlint
	- [remark-lint](https://github.com/remarkjs/remark-lint)
- Swift:
	- SwiftLint
- Go:
	- Revive
	- Gofmt
- Kotlin:
	- Detekt
	- [ktlint](https://github.com/pinterest/ktlint)
	- Android Lint
	- [SonarLint](https://www.sonarlint.org/)
- C/C++:
	- cppcheck
	- cpplint
	- [SonarLint](https://www.sonarlint.org/)
- Rust:
	- rustfmt
	- [Clippy](https://github.com/rust-lang/rust-clippy)
- Java:
	- Google Java Format
	- Android Lint
	- [Error Prone](https://github.com/google/error-prone)
	- [SpotBugs](https://github.com/spotbugs/spotbugs)
	- [PMD](https://github.com/pmd/pmd)
	- [SonarLint](https://www.sonarlint.org/)
- SQL:
	- [PHP-SQLlint](https://cweiske.de/tagebuch/php-sqllint.htm)
	- [SqlFluff](https://github.com/alanmcruickshank/sqlfluff)
- JSON:
	- [JSON Lint](https://github.com/zaach/jsonlint)
	
	See [JSONLint - The JSON Validator](https://jsonlint.com/)
- YAML:
	- [yamllint](https://github.com/adrienverge/yamllint)
	
	See [YAMLlint - The YAML Validator](http://www.yamllint.com/)
- Dart:
	- dartfmt
	
	See [dart-lang/dart_style: An opinionated formatter/linter for Dart code](https://github.com/dart-lang/dart_style)
- VBA/VB.Net:
	- [Rubberduck](https://github.com/rubberduck-vba/Rubberduck/)
	- [SonarLint](https://www.sonarlint.org/)
- XML/XSL:
	- [PMD](https://github.com/pmd/pmd)
- C#:
	- [SonarLint](https://www.sonarlint.org/)
- PO:
	- [Dennis](https://dennis.readthedocs.io/en/latest/linting.html)
	
- git repository: repolinter
- commit message: [commitlint](https://commitlint.js.org/)
- website/webpage:
	- [webhint](https://github.com/webhintio/hint)
	- [axe-core](https://github.com/dequelabs/axe-core) (accessibility)
	- [Size Limit](https://github.com/ai/size-limit/) (webperf)
	- [YozhikM/stylelint-a11y: Plugin for stylelint with a11y rules](https://github.com/YozhikM/stylelint-a11y) (accessibility)
- Pull request: [Danger JS](https://github.com/danger/danger-js)
- text:
	- [yaspeller](https://github.com/hcodes/yaspeller)
	- [textlint](https://github.com/textlint/textlint)
- [sindresorhus/awesome-lint: Linter for Awesome lists](https://github.com/sindresorhus/awesome-lint)
- [hcodes/yaspeller: Search tool typos in the text, files and websites](https://github.com/hcodes/yaspeller)

- [okonet/lint-staged: 🚫💩 — Run linters on git staged files](https://github.com/okonet/lint-staged)
- [Introducing a fully extendable eslint plugin for JSON i18n translation files — GoDaddy Engineering Blog](https://godaddy.github.io/2018/04/02/introducing-eslint-plugin-i18n-json/)

## Team work

- [How to do a code review | eng-practices](https://google.github.io/eng-practices/review/reviewer/)
- lint
- CI
- [bradfrost/frontend-guidelines-questionnaire: A one-page questionnaire to help your team establish effective frontend guidelines, so that you can write consistent & cohesive code together.](https://github.com/bradfrost/frontend-guidelines-questionnaire)

## Source code organisation

	/build (bin|export|dist) - a (pre-)compiled version of your library/app 
	/docs (documentation) - possibly in .md .html or .txt so no compiling is needed in order to read them
		/{ISO 639-1 code} - if localized docs
	/examples - demos of your library or sample files
	/src (sources)
		/data (assets|resources|res) - assets you need
		/libs (vendor|libraries) - libraries you depend on
		/in as many folders as needed - your own code
		main entry file (e.g. main.cpp, index.html)
	/tests - unit tests
	/utils - utilities for building and stuff
	LICENSE
	README
	.gitignore (or similar)

- [Usable open source repositories | soledad penadés](http://soledadpenades.com/2013/04/07/usable-open-source-repositories/)
- [directory structure - What is the difference between the "lib" and "vendor" folders? - Programmers Stack Exchange](http://programmers.stackexchange.com/questions/123305/what-is-the-difference-between-the-lib-and-vendor-folders)

## Version control system

Aka VCS

See also [Git](./Git/Git.md)

### Store only sources without configuration

**Don't store configuration files, especially if contains password, private keys, etc.** Ignore configuration files, but provide an configuration example file

- [StackExchange/blackbox: Safely store secrets in Git/Mercurial/Subversion](https://github.com/StackExchange/blackbox)
- [Check hash and keys leak or reversed (hashes)](../Security/Security.md#hash-and-keys)

**Store only sources**, nothing else can be computed / recreated. If you need it, use submodules or a [package manager](https://en.wikipedia.org/wiki/Package_manager).
Store only data is part of the software. If it's content like blog content (mysql dump) store it with an other way or with a submodule.
The question is: resource that belong to the project or are projects them-selves? Store it in the same VCS or as dependency (submodule) or with another solution (like SQL dump)

Ex: App Code + precompiled lib/binaries submodule (will be used to include thrid party code)

If images are part of the software:
App Code + (exported) PNGs or AppCode + design (PSD) submodule (will be used to generate icons automatically, etc.)

- [version control - Managing large binary files with Git - Stack Overflow](https://stackoverflow.com/questions/540535/managing-large-binary-files-with-git)
- [version control - Should images be stored in a git repository? - Software Engineering Stack Exchange](https://softwareengineering.stackexchange.com/questions/80962/should-images-be-stored-in-a-git-repository)
- [Working with large files - GitHub Help](https://help.github.com/en/github/managing-large-files/working-with-large-files)
- [How to ignore changes in git submodules | /bb|\[ˆb\]{2}/](http://www.nils-haldenwang.de/frameworks-and-tools/git/how-to-ignore-changes-in-git-submodules) (add `ignore = dirty` for each submodule in `.gitmodules`)

### Monorepo

> Most developers can view and propose changes to files anywhere across the entire codebase, with only a few exceptions

- [Don't ask if a monorepo is good for you – ask if you're good enough for a monorepo](https://yosefk.com/blog/dont-ask-if-a-monorepo-is-good-for-you-ask-if-youre-good-enough-for-a-monorepo.html) - [Monorepo is great if you're really good | Hacker News](https://news.ycombinator.com/item?id=20565017)
- [Why Google Stores Billions of Lines of Code in a Single Repository | July 2016 | Communications of the ACM](https://cacm.acm.org/magazines/2016/7/204032-why-google-stores-billions-of-lines-of-code-in-a-single-repository/fulltext) - [Why Google Stores Billions of Lines of Code in a Single Repository – Google AI](https://ai.google/research/pubs/pub45424)

### Version message

Aka Git commit message.

Use verbes:

- Add: Create a capability e.g. feature, test, dependency
- Cut: Remove a capability e.g. feature, test, dependency
- Fix: Fix an issue e.g. bug, typo, accident, misstatement
- Bump: Increase the version of something e.g. dependency
- Make: Change the build process, or tooling, or infra
- Start: Begin doing something; e.g. create a feature flag
- Stop: End doing something; e.g. remove a feature flag
- Refactor: A code change that MUST be just a refactoring
- Reformat: Refactor of formatting, e.g. omit whitespace
- Optimize: Refactor of performance, e.g. speed up code
- Document: Refactor of documentation, e.g. help files

- [How to write the perfect pull request - The GitHub Blog](https://github.blog/2015-01-21-how-to-write-the-perfect-pull-request/)
- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
- [joelparkerhenderson/git_commit_message: Git commit message: how to write a good git commit message](https://github.com/joelparkerhenderson/git_commit_message)
- [Bug Prediction at Google](https://google-engtools.blogspot.fr/2011/12/bug-prediction-at-google.html) - Use Git version message to predict spot bugs
- [How to Write a Git Commit Message (2014) | Hacker News](https://news.ycombinator.com/item?id=13889155)
- [Karma - Git Commit Msg](http://karma-runner.github.io/1.0/dev/git-commit-msg.html)
- [How to Get More Out of Your Git Commit Message - datree](https://datree.io/blog/git-commit-message-conventions-for-readable-git-log/)

## Indentation

Aka Spaces vs tabs

- people can set the indentation render size to whatever they prefer in a way that doesn't affect other users (2-space indentation can be hard to read)
- it's faster to move around only using the keyboard (IDE can handle that)
- most IDE can swith/convert one to the other
- tab is a character specifically meant for indentation (in fact they are meant for tabulation)
- it's impossible to half-indent something with tabs
- store a tab char use less space than spaces
- tabs for indentation, spaces for alignment:
	
		[tab]void someNiceMethod(
		[tab][space*20]int arg1
		[tab])

	Or allow only simplier indentation:

		[tab]void someNiceMethod(
		[tab][tab]int arg1
		[tab])

- [Tabs versus Spaces](https://www.jwz.org/doc/tabs-vs-spaces.html)
- [Why tabs are clearly superior | Lea Verou](http://lea.verou.me/2012/01/why-tabs-are-clearly-superior/) - see also links
- [Tabs or Spaces](https://ukupat.github.io/tabs-or-spaces/)
- [Indent style — Wikipedia](https://en.wikipedia.org/wiki/Indent_style)
- [Indentation (typesetting) — Wikipedia](https://en.wikipedia.org/wiki/Indentation_%28typesetting%29#Indentation_in_programming)
- [Tab key — Wikipedia](https://en.wikipedia.org/wiki/Tab_key)
- [Death to the Space Infidels!](https://blog.codinghorror.com/death-to-the-space-infidels/)
- [Joonathan Mägi's answer to Why would a coder use spaces over tabs? - Quora](https://www.quora.com/Why-would-a-coder-use-spaces-over-tabs/answer/Joonathan-M%C3%A4gi)
- [Developers who use spaces make more money than those who use tabs | Hacker News](https://news.ycombinator.com/item?id=14560042) - it's incorrect interpretation of data, see [Tabs, spaces and your salary - how is it really?](http://evelinag.com/blog/2017/06-20-stackoverflow-tabs-spaces-and-salary/index.html)
- [tom tom dot com on Twitter: ""Spaces or tabs?" "Semicolons." @aisamanra https://t.co/QmiH4t79gN"](https://twitter.com/pelotom/status/779134762283732992) - C with semicolons as indentation char

## Release note

See [Release note](../Documentation/Documentation.md#release-note)

## Game dev

- Use a framerate, and compute all physics on that in each frames, compute the number of frames must be computed with the delta time or within a loop (for replay, as anti-cheat method)
- store all account activity (connections, change status/state, name, email, password, login, logout, rights, game start, game end, etc.)
- separate user account and user logins (email, native, OAuth, etc.)
- clients don't always have the right time (time offset of few seconds/minutes)

Anticheat:

- use a replay engine (simulation)
- save IP, device type, connection type, client revision/version, server revision/version, etc.
- save input and output (see below)
- use a seed (a PRNG) for random, you could use it for only short timelapse the client need to retrive at defined delay (ex: each 10 seconds need to get a new seed from the server). If in the timeframe the client can't get the new seed, it's a asychronous issue. The player is disconnected (the game end) or the game paused until the seed is retrived.
	Or use server side event to be sure the server control randomness continuously

For replay, be sure:

- your engine should use fixed framerate
- nothing should be based on time, but on frames (store results in engine frames, not time units)
- be sure sorted items are stable (what happend when 2 elements have the same compared value)
- consider all external values that could modify states
- record input and all values (objects position, states)

- [Game Programming Patterns](http://gameprogrammingpatterns.com/) - [munificent/game-programming-patterns: Source repo for the book](https://github.com/munificent/game-programming-patterns)

## License

> This file incorporates work covered by the following copyright and permission notice:” followed by the original copyright and license copied in

- [Choose an open source license | Choose a License](https://choosealicense.com/)
- [The Legal Side of Open Source | Open Source Guides](https://opensource.guide/legal/)
- [Permissive software license - Wikipedia](https://en.wikipedia.org/wiki/Permissive_software_license)
- [License compatibility - Wikipedia](https://en.wikipedia.org/wiki/License_compatibility)

# Concepts and Methodology

> Just because you can't see it, doesn't mean it isn't there.
— http://www.awbnetwork.org/campaigns/item/49-what-lies-under.html

> Telling a programmer there's already a library to do X is like telling a songwriter there's already a song about love.
— Pete Cordell

- [Global Variables Are Bad](http://c2.com/cgi/wiki?GlobalVariablesAreBad)
- [Programming paradigm — Wikipedia](https://en.wikipedia.org/wiki/Programming_paradigm)
- [Travis CI - Test and Deploy Your Code with Confidence](https://travis-ci.org/)
- [Naming convention (programming) — Wikipedia](https://en.wikipedia.org/wiki/Naming_convention_%28programming%29)
- [Template:Computer science — Wikipedia](https://en.wikipedia.org/wiki/Template:Computer_science)
- [Template:Software engineering — Wikipedia](https://en.wikipedia.org/wiki/Template:Software_engineering)
- [Template:Systems engineering — Wikipedia](https://en.wikipedia.org/wiki/Template:Systems_engineering)

## API

Aka application programming interfaces

Simplicity Matters, [KISS](../Conception/Conception.md#kiss)

[Rails Conf 2012 Keynote: Simplicity Matters by Rich Hickey](https://www.youtube.com/watch?v=rI8tNMsozo0)

> Framework guide:
> 
> - Can an idiot decipher your errors?
> - Can an idiot read the code?
> - Can an idiot make something quickly without a tutorial?
— https://twitter.com/elsassph/status/557866984705380352

See also:

- [Web API](../Web/Web.md#api)
- [API documentation](../Documentation/Documentation.md#api)
- [Error messages documentation](../Documentation/Documentation.md#error-messages)

## MVC

- [architecture - In MVC should a model handle validation? - Software Engineering Stack Exchange](https://softwareengineering.stackexchange.com/questions/97880/in-mvc-should-a-model-handle-validation)
- [View Controller Programming Guide for iOS: The Role of View Controllers](https://developer.apple.com/library/content/featuredarticles/ViewControllerPGforiPhoneOS/)
- [View Controller Programming Guide for iOS: Presenting a View Controller](https://developer.apple.com/library/content/featuredarticles/ViewControllerPGforiPhoneOS/PresentingaViewController.html)

## Data

Aka model, storage

- [NoSQL Data Modeling Techniques – Highly Scalable Blog](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/)

See also [CMS](Web#cms)

## Coding font

- [microsoft/cascadia-code: This is a fun, new monospaced font that includes programming ligatures and is designed to enhance the modern look and feel of the Windows Terminal.](https://github.com/microsoft/cascadia-code)

## Outline

Also called Document map.

Outline important elements like :

- pages
- sections and sub-sections
- titles and sub-titles
- Objects : packages, classes, methods, properties, etc.

## Minimap

Graphical dezomed view of document like navigator panel in Photoshop

## Code hightlighting

## Code flow

Save all calls, contexts (like closures), parameters, time, duration

## Unit tests

Graphical test: image capture

Structural test: DOM capture (CSS and HTML for each nodes and tree nodes)

## Code reload

- live reloading: reload completely, loose the app state
- hot reloading: reload partial parts, but keep current app state

Works easily for [declarative code](https://en.wikipedia.org/wiki/Declarative_programming). It's more complicated for [imperative code](https://en.wikipedia.org/wiki/Imperative_programming) (or [procedural code](https://en.wikipedia.org/wiki/Procedural_programming)), where the code controle the app state with control flow

> Declarative programming contrasts with imperative and procedural programming. Declarative programming is a non-imperative style of programming in which programs describe their desired results without explicitly listing commands or steps that must be performed

- [javascript - What is the difference between Hot Reloading and Live Reloading in React Native? - Stack Overflow](https://stackoverflow.com/questions/41428954/what-is-the-difference-between-hot-reloading-and-live-reloading-in-react-native/41429055#41429055)

## Continuous integration and continuous delivery

- [Travis CI - Test and Deploy Your Code with Confidence](https://travis-ci.org/)
- [Deploys at Slack - Several People Are Coding](https://slack.engineering/deploys-at-slack-cd0d28c61701)

## Vagrant

## Autocomplete

## Programming methods

### Chaining

	displayObject.setX(10).setY(20).setAlpha(0.5).setRotation(180);

	$aMembers = $this->m_pMembers
		->join('jobs')
		->join('orders')
		->fetchAll($szFields, $szConditions);

Vs.

	$this->m_pMembers->join('jobs');
	$this->m_pMembers->join('orders');
	$aMembers = $this->m_pMembers->fetchAll($szFields, $szConditions);  

- http://en.wikipedia.org/wiki/Method_chaining
- http://en.wikipedia.org/wiki/Fluent_interface

See also [Method cascades]

### Method cascades

Supported in Dart language via `..`

	displayObject = new DisplayObject();
	..x = 10;
	..y = 20;
	..alpha = 0.5;
	..rotation = 180;

Vs.

	displayObject = new DisplayObject();
	displayObject.x = 10;
	displayObject.y = 20;
	displayObject.alpha = 0.5;
	displayObject.rotation = 180;

See also [Chaining]

### Goto

Some languages don't have goto keyword, but a loop with conditional (switch or if-else) can be used.

- [C JSON parser using a jump table](https://github.com/quartzjer/js0n/blob/master/src/js0n.c)

### Query

Query languages

- E4X: `displayList..(x == 20)`
- SQL
- XPath
- LINQ
- CSS (ex: )

- http://en.wikipedia.org/wiki/Query_language
- http://jsonselect.org/#overview
- https://developer.mozilla.org/en-US/docs/CSS/Getting_Started/Selectors
- https://developer.mozilla.org/en-US/docs/DOM/document.querySelectorAll

### Sync/ASync process

- http://en.wikipedia.org/wiki/Asynchronous_I/O
- http://en.wikipedia.org/wiki/DOM_events
- http://en.wikipedia.org/wiki/Event_%28computing%29
- https://en.wikipedia.org/wiki/Observer_pattern
- http://en.wikipedia.org/wiki/C_Sharp_syntax#Events
- http://en.wikipedia.org/wiki/Event-driven_programming

- Callback: `connection.load(callback, errorcallback, params…);`, `var intervalID = setInterval(callback, params…); clearInterval(intervalID);`
- W3C DOM0, Traditional Event Handler: `connection.onload = callback; connection.onerror = errorcallback; connection.load();`
- W3C DOM2 (Observer pattern): `connection.addEventListener("load", callback); connection.addEventListener("error", callback); connection.load()`
- `java.util.Observer` and `java.util.Observable` (Observer pattern) 
- Signal (AS3Signal): https://github.com/robertpenner/as3-signals
- Other: event SuperClass listener (listen all ErrorEvent), condition event, delayed event (dispatch when a listener is added), first time event listener

### Object and Procedural

	object.method(param1);

Vs.

	function(object, param1)

In ECMAScript, `function` have context:

	var bindedFunction = object.function.bind(object);
	bindedFunction(param1);
	//eq.
	object.function(param1);
	//eq.
	bindedFunction.call(object, param1);

- http://en.wikipedia.org/wiki/Programming_paradigm
- https://developer.mozilla.org/en-US/docs/JavaScript/Reference/Global_Objects/Function/apply
- https://developer.mozilla.org/en-US/docs/JavaScript/Reference/Global_Objects/Function/bind

### Blocking, non blocking (usage of events)

### DRY (Don't repeat yourself)

- [Don't repeat yourself - Wikipedia, the free encyclopedia](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)

### YAGNI (You aren't gonna need it)

- http://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it

### KISS (Keep It Simple, Stupid)

- [KISS principle - Wikipedia, the free encyclopedia](https://en.wikipedia.org/wiki/KISS_principle)
- [The Kiss Principle](http://people.apache.org/~fhanik/kiss.html)

## Sub-language/template

String data could contains injection points or processing instructions

- PHP can contains part of HTML (specialy outside processing instruction, inside strings / HEREDOC)
- HTML can contains CSS (in `style` tags) or JavaScript (inside `script` tags) or any other language like human language (en, fr, etc. in any tag) or machine language (inside `pre`, `code`, `script` tags) 
- PHP can contains SQL (inside strings / HEREDOC)
- JavaScript can contains HTML or CSS (inside strings)
- HTML can contains JS or CSS

## Tests

> Tests are a specification
> The most important role of unit tests in your code is to provide an executable specification of what the code is supposed to do. Even if the test code is wrong, or the code has bugs, the knowledge of what the system is supposed to do is priceless.

> Unit testing forces you to feel the pain of bad design up front
— Michael Feathers

> Good unit tests share a lot of the following characteristics:
> 
> - Fast - should run in milliseconds.
> - No network access - should be able to turn off wireless/unplug and all the tests still pass.
> - Limited file system access - this adds to speed and flexibility if deploying code to other environments.
> - No database access - avoids costly setup and teardown activities.
> - Test only one thing at a time - a unit test should have only one reason to fail.
> - Well-named - see 5.2 above.
> - Mostly fake objects - the only "real" objects in unit tests should be the object we're testing and simple value objects. The rest should be some form of test double

> If a class is hard to test, it's a design flaw. Different flaws manifest themselves in different ways, though. If you have to do a ton of mocking, your class probably has too many dependencies, or your methods are doing too much.

## Design pattern

- [Design Patterns for Humans](https://github.com/kamranahmedse/design-patterns-for-humans)
- [Design Patterns — Wikipedia](https://en.wikipedia.org/wiki/Design_Patterns)
- [Are design patterns compatible with modern software techniques? | The random utterances of David Arno](http://www.davidarno.org/2013/06/17/are-design-patterns-compatible-with-modern-software-techniques/)
- [Category Category](http://wiki.c2.com/?CategoryCategory) - Patterns

### Visitor pattern

- [Home - Documentation](http://api.postcss.org/) - PostCSS use vistor pattern
- [Visitor pattern — Wikipedia](https://en.wikipedia.org/wiki/Visitor_pattern)

### Command

- command
- receiver
- invoker
- client
 
	using System;
	using System.Collections.Generic;
	
	namespace CommandPattern
	{
	  public interface ICommand
	  {
	    void Execute();
	  }
	  
	  public class Switch
	  {
	    private List _commands = new List();
	    public void StoreAndExecute(ICommand command)
	    {
	      _commands.Add(command);
	      command.Execute();
	    }
	  }
	  
	  public class Light
	  {
	    public void TurnOn()
	    {
	      Console.WriteLine("The light is on");
	    }
		
	    public void TurnOff()
	    {
	      Console.WriteLine("The light is off");
	    }
	  }
	  
	  public class FlipUpCommand : ICommand
	  {
	    private Light _light;
		
	    public FlipUpCommand(Light light)
	    {
	      _light = light;
	    }
		
	    public void Execute()
	    {
	      _light.TurnOn();
	    }
	  }
	  
	  public class FlipDownCommand : ICommand
	  {
	    private Light _light;
		
	    public FlipDownCommand(Light light)
	    {
	      _light = light;
	    }
		
	    public void Execute()
	    {
	      _light.TurnOff();
	    }
	  }
	  
	  internal class Program
	  {
	    public static void Main(string[] args)
	    {
	      Light lamp = new Light();
	      ICommand switchUp = new FlipUpCommand(lamp);
	      ICommand switchDown = new FlipDownCommand(lamp);
		  
	      Switch s = new Switch();
	      string arg = args.Length &gt; 0 ? args[0].ToUpper() : null;
	      if (arg == "ON")
	      {
	        s.StoreAndExecute(switchUp);
	      }
	      else if (arg == "OFF")
	      {
	        s.StoreAndExecute(switchDown);
	      }
	      else
	      {
	        Console.WriteLine("Argument \"ON\" or \"OFF\" is required.");
	      }
	    }
	  }
	}

Or simply:

	using System;
	using System.Collections.Generic;
	
	namespace CommandPattern
	{
	  public static class Program
	  {
	    private static readonly Dictionary Commands =
	      new Dictionary
	      {
	        { "ON", () => Console.WriteLine("The light is on") },
	        { "OFF", () => Console.WriteLine("The light is off") }
	      };
		 
	    private static void Main(string[] args)
	    {
	      if (args.Length == 1 && Commands.ContainsKey(args[0]))
	      {
	        Commands[args[0]]();
	      }
	      else
	      {
	        Console.WriteLine("Argument \"ON\" or \"OFF\" is required.");
	      }
	    }
	  }
	}

### Observer
