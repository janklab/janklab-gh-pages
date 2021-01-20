---
title: Janklab
layout: default
---

Janklab is a suite of free and open source programming libraries for [Matlab](https://www.mathworks.com/products/matlab.html). It contains general-purpose programming utilities, advanced HTML email generation, and more.

Janklab is written from the perspective of a software developer with a background in more mainstream programming languages, but some parts of it are intended for easy use by typical Matlab users.

Janklab is a project of [Andrew Janke](https://apjanke.net).

## License

All the Janklab libraries are licensed under the business-friendly Apache or BSD 2-Clause licenses. It's fine to use Janklab in commercial or proprietary software.

## Component Libraries

* [**Janklab**](https://github.com/janklab/janklab) – The core Janklab library is a collection of various utilities and APIs, and represents Andrew's accumulation of a base "core Matlab environment" for doing nontrivial programming. It includes:
  * additional date/time classes
  * MDBC, a powerful and high-performance Database Toolbox extension layer
  * an API for Excel I/O (that doesn't require Excel to be installed!)
  * a bunch of miscellaneous stuff
* [**SLF4M**](https://github.com/janklab/SLF4M) – A simple but powerful logging framework for Matlab, like Java's [SLF4J](http://www.slf4j.org/).
* [**dispstr**](https://github.com/janklab/dispstr) – A customizable, polymorphic object display API. (That sounds boring, but trust me, it's actually really cool!)
* [**MCodeNavigator**](https://github.com/janklab/MCodeNavigator) – A code-structure-aware GUI browser for Matlab source code, like many IDEs have.
* [**MailSpoon**](https://mailspoon.janklab.net) – Sophisticated HTML email generation in Matlab.
* [**MatlabProjectTemplate**](https://github.com/janklab/MatlabProjectTemplate) – A template for creating Good source code layouts for Matlab software development projects.
* [**matlab-bench**](https://github.com/janklab/matlab-bench) – The Matlab OOP benchmark behind [that one "Is Matlab OOP Slow?" Stack Overflow answer](https://stackoverflow.com/a/1745686/105904).
* [**Matlab-JUMP**](https://github.com/janklab/matlab-jump) – A little dependency-management tool for writing custom Java code for use in a Matlab environment.
* [**matlab-jarext-inspector**](https://github.com/janklab/matlab-jarext-inspector) – Shows you what Java JARs Matlab is bundling.

The various Janklab libraries have dependencies on and are bundled with various other open source libraries. See individual library documentation for details.

## More Documentation

* [FAQ](FAQ.html)

## Development and Support

Janklab development is hosted [on GitHub](https://github.com/janklab). You can file bug reports or feature requests as issues on the library-specific GitHub repo.

Everything in Janklab is in either the experimental or beta stage of development. Use caution!

Support for Janklab is free, and is on an as-available/best-effort/if-I-feel-like-it basis. You might also try dropping by [the Matlab Discord](https://discord.gg/bBMbNCT), where I and several other Matlab experts hang out; it's a great place to get Matlab help.

Lots of Janklab is built on other open source projects, and a lot of it takes the form of Matlab binding layers for FLOSS libraries in other languages. Thanks to all the other FLOSS developers out there!

## History

I spent about ten years building Matlab platforms in the financial sector, with a focus on data analysis, "productionization", and integrating Matlab with other systems and languages. During that time I developed some strong opinions about what you needed to add to Matlab to make it a decent development environment. And when I had some time off, I decided to Do It Right and build out some utilities based on what I had learned, but with modern Matlab coding practices.

After that, I did some consulting writing Matlab programs for people, and decided to collect all my various utility code in one place, so I didn't have to spend client time rewriting this "base layer" for every project. I open sourced it to formalize the license my clients received this common code under, and to have something of a public portfolio for myself, since all my prior finance work was highly proprietary.

## About Andrew

[Andrew Janke](https://apjanke.net) has about twenty years of industry experience building software platforms, with much of that involving Matlab. He started out in the weather software industry, and then got recruited by a [Citadel Investments](https://www.citadel.com) and spent 15 years in finance, working closely with trading staff to develop analytical and trading platforms.

Andrew is currently Director of Quantitative Systems at [Demex Technologies](https://thedemexgroup.com).
