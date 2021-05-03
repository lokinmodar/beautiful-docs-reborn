# History
On Sunday, May 2nd, 2021 someone shared the root repository with me. And this line stood out to me:
> **DO YOU WANT TO BUILD AND WRITE GLORIOUS TECHNICAL DOCUMENTATION FULL TIME? EMAIL mark@helium.com. WE NEED YOU.**

It was a time-capsule, as the repo hadn't had any updates in 5 years. But though it was silly, I couldn't resist. On a whim I tried emailing, because I'd just entered a phase of looking for my next career step. Don't know if I'll hear back, but meanwhile, I see there's a lot of community contributions after that last update that were never processed...so, I thought it might be interesting to apply a little of that myself. 

I'm not personally brave enough to post my own email address here, but I still plan on checking GitHub notifications if you file an issue or PR. 

# Beautiful Docs

I love documentation. If you work with/are writing code intended for usage and consumption by more than one person, you should love it, too. Documentation and other resources will make or break the success of your project. And the more open and collaborative you want development to be, the more crucial docs become.

With that in mind, here's a list of docs and other developer resources that myself and others find particularly useful, well-written, and otherwise "beautiful." May they serve to inspire you when writing and designing yours. Thanks to various contributors, we now also have sections dedicated to [Writing about Documentation](#writing-about-docs) and [Tools for Generating Docs](#generating-docs).

This should be updated fairly regularly. As usual, **pull requests are encouraged**. 
* If you're contributing a link, be sure to include a few words on why you're adding it and some sort of self-attribution so that people can know from whom it came.
* All docs are listed in the order they were added. Keep this order when submitting your PR. 

[Mark](https://twitter.com/pharkmillups)

### And Now For The Docs 

* [Redis Commands](https://redis.io/commands) - Most of the Redis docs are exceptional, but this section really epitomizes the combination of good design and usability. And all the individual command pages give you the ability to test things out without leaving the page. Pretty close to perfect.
* [GitHub Developer Docs](https://developer.github.com/v3/) - I don't always get excited about accordion-based navigation, but when I do...
* [Dropwizard](https://www.dropwizard.io/) - Beautiful and concise; another Bootstrap joint. (contributed by [mrtazz](https://twitter.com/#!/mrtazz)).)
* [Riak Pipe README](https://github.com/basho/riak_pipe/blob/develop-3.0/README.org) - The simplicity of READMEs means that you can't obscure shitty content with flashy design. This one is written by my Basho colleague [Bryan Fink](https://twitter.com/#!/hobbyist) and should be committed to memory as an excellent example of how to write READMEs.
* [Learn You Some Erlang](https://learnyousomeerlang.com/content) (contributed by [@lenary](https://twitter.com/lenary)) (It should also be noted that LYSE was inspired by Miran Lipovača's **NOT-HTTPS** [Learn You A Haskell](http://learnyouahaskell.com/).)
* [CoreOS](https://coreos.com/docs/) - Primary-colored goodness and a distributed system to boot (contributed by [@lucperkins](https://twitter.com/lucperkins))
* [Django Documentation](https://docs.djangoproject.com/en/) - (contributed by [@bretthoerner](https://twitter.com/bretthoerner))
* [Clojuredocs.org](https://clojuredocs.org) (contributed by [@mrb_bk](https://twitter.com/#!/mrb_bk))
* [FreeBSD Handbook](https://www.freebsd.org/handbook/) - Clean and direct documentation of an OS. (contributed by [@mrtazz](https://twitter.com/#!/mrtazz))
* [Ruby on Rails Guides](https://guides.rubyonrails.org/) - (contributed by [@seancribbs](https://twitter.com/#!/seancribbs))
* **NOT-HTTPS** [Pow Annotated Source](http://pow.cx/docs/) - Built with [docco.](https://github.com/jashkenas/docco) (contributed by [@BonzoESC](https://twitter.com/BonzoESC))
* [Stripe Documentation](https://stripe.com/docs) and [Full API Documentation](https://stripe.com/docs/api) - Multiple languages, example code, good detail on the API; especially love how the API docs show examples for curl and their supported client libraries. (contributed simultaneously by [@tnm](https://twitter.com/#!/tnm) and [@technoweenie](https://twitter.com/#!/technoweenie))
* [Librato Developer Docs](https://www.librato.com/docs/api/) - Librato's RESTful API documentation. (contributed by [@josephruscio](https://twitter.com/josephruscio))
* [CoffeeScript](https://coffeescript.org/) - (contributed by [@joedevivo](https://twitter.com/#!/joedevivo))
* [Why's (Poignant) Guide to Ruby](https://poignant.guide/) - (contributed by [@joedevivo](https://twitter.com/#!/joedevivo))
* [Twitter Bootstrap](https://getbootstrap.com/) - Documented the project using the project. (contributed by [@kylewest](https://twitter.com/kylewest))
* [hogan.js](https://twitter.github.io/hogan.js/) - Simple and Beautiful. (contributed by [@kylewest](https://twitter.com/kylewest))
* [Scala Documentation](https://docs.scala-lang.org/) - Beautifully-styled Scala documentation site. (Contributed by [David M. Lee](https://github.com/leedm777))
* [Linode Guides and Tutorials](https://www.linode.com/docs/) (contributed by [@davidmatas](https://twitter.com/#!/davidmatas))
* [Brighter Planet API](https://brightplanet.com/data-feed-api-guide/) (contributed by Derek Kastner - no active link)
* [Symfony2 Docs](https://symfony.com/doc/current/) (contributed by [Rodney Keeling](https://github.com/rodneykeeling))
* [Number Laundry API](https://github.com/WhatCheer/Number-Laundry) - Fun design, simple examples. (contributed by [@jmhobbs](https://twitter.com/jmhobbs))
* [Underscore.js](https://underscorejs.org) - Simple, clean, single page. (contributed by [@twe4ked](https://twitter.com/twe4ked))
* [Qt](https://doc.qt.io/) - Very comprehensive documentation with tutorials and guides and great examples. (contributed by [@nikhilcutshort](https://twitter.com/nikhilcutshort))
* [CasperJS](https://github.com/casperjs/casperjs) - CasperJS is a navigation scripting & testing utility for PhantomJS, written in Javascript. (contributed by [@n1k0](https://twitter.com/n1k0))
* **NOT-HTTPS** [rubyamqp.info](http://rubyamqp.info) - A number of in-depth guides that cover Ruby `amqp` gem but also try to explain AMQP 0.9.1 features, why they exist, and how they are supposed to be used. (contributed by [Michael Klishin](https://twitter.com/#!/michaelklishin/))
* **NOT-HTTPS** [Savon.rb](http://savonrb.com/) - (contributed by [Mathias Meyer](https://twitter.com/#!/roidrage))
* [Android Developer Documentation](https://developer.android.com/docs) (contributed by [Rajeev N B @rBharshetty](https://twitter.com/#!/rBharshetty))
* [ØMQ - The Guide](https://zguide.zeromq.org/page:all) - Exciting documentation for an exciting lib. Concise working code examples available in multiple languages. Concepts are explained clearly. (contributed by [kindkid](https://github.com/kindkid))
* [Postmark Developer Docs](https://developer.postmarkapp.com/) - Simple, easy to navigate, informative.
* [Twitter Developers Docs](https://dev.twitter.com/docs) - In-depth and very well organized. (contributed by [@tsantero](https://twitter.com/#!/tsantero))
* [GitHub Styleguide](https://github.com/styleguide) - Pragmatic styleguide with sections on Ruby, JavaScript and CSS. (https://twitter.com/github) (contributed by [@lenary](https://twitter.com/#!/lenary))
* [Moment.js](https://momentjs.com/docs) - Thorough, well-designed, and excellent use of top-nav. (contributed by [@joshuapoehls](https://twitter.com/#!/joshuapoehls))
* [Solarized](https://ethanschoonover.com/solarized) - Beautiful documentation about a color scheme, using the color scheme from [Ethan Schoonover](https://github.com/altercation). (contributed by [@seancribbs](https://twitter.com/seancribbs))
* [Ember.js](https://guides.emberjs.com/) - The overall navigation could be done a bit better but the presentation and readability is quite nice. (contributed by [@cmeik](https://twitter.com/cmeik))
* [Riak Docs](https://docs.riak.com/) (aka formerly "basho") - Well-designed, excellent use of versioning, integrated search, and much more.
* [Go By Example](https://gobyexample.com/) - Clean, simple, and extensive. These docs that make you want to learn Go just because they make it so straightforward.
* [gevent API Docs](https://www.gevent.org/intro.html) - Clean, polished docs for gevent. (contributed by [rubik](https://github.com/rubik))
* **NOT-HTTPS** [CodernityDB](http://labs.codernity.com/codernitydb/index.html) - Clean, extensive, useful. I also love the fact that the day the software was released the documentation was this extensive.
* [Riemann](https://riemann.io/) - Great design, easy to read, and very thorough with introductory and advanced topics.
* [Pretty RFC](https://pretty-rfc.herokuapp.com/) - Reworked [IETF](https://www.ietf.org) documents for easier viewing.
* [Vagrant](https://www.vagrantup.com/docs/) - Well organized, easy to read, attractive design. ([@clstokes](https://twitter.com/clstokes))
* [Wolfram Language](https://reference.wolfram.com/language/) - Nice top-level navigation in a grid layout. Topics grouped by color, each with a relevant graphic and on-click menu of sub-topics. (contributed by [troytop](https://github.com/troytop))
* [Lisp Flavored Erlang: Quick Start](https://lfe.gitbooks.io/quick-start/content/) - Attractive presentation, nice jumpstart for the language. (contributed by [@macintux](https://twitter.com/macintux))
* **NOT-HTTPS** [Thinking Forth](http://thinking-forth.sourceforge.net) - Forth is now largely eclipsed by Factor, but the book remains an inspiring look at the ideas behind this stack-based language. (contributed by [@macintux](https://twitter.com/macintux))
* [Packer Documentation](https://www.packer.io/docs) - These are just lovely.
* **NOT-HTTPS** [Abjad: Modeling Music in Python](http://abjad.mbrsi.org/) - Clean styling, and impressive integration of figures and diagrams. (contributed by [@adorsk](https://github.com/adorsk))
* [SqlAlchemy](https://docs.sqlalchemy.org/) - One of the most comprehensive pieces of documentation I've ever seen, with excellent linking and layout. (contributed by [@adorsk](https://github.com/adorsk))
* [Sonata Project](https://sonata-project.org/bundles/) - All the Sonata Project bundles for Symfony2 on a single page. These have a nice, clear layout. (contributed by @NoScopie (non-active profile))
* [Laravel](https://laravel.com/docs) - Easily-readable and well-organized docs. Navigation is well formatted and articles are easy to consume. (contributed by [@ToddSmithSalter](https://github.com/toddsmithsalter))
* [FullCalendar](https://arshaw.com/fullcalendar/docs/) – Concise overview of all APIs on a single page, and in-depth descriptions for each. (contributed by [@gr2m](https://github.com/gr2m/))
* [Rust Guides](https://doc.rust-lang.org/book/README.html) - Rust is a stable and memory-safe language and the docs (written by [Steve Klabnik](https://github.com/steveklabnik)) are clearly a high priority. The guides in particular illustrate core concepts of the standard library in a conversational, accessible style. (contributed by [Nick Cox](https://github.com/thenickcox))
* [MongoDB Manual](https://docs.mongodb.org/manual/) - Easy to navigate, clean, carefully and well designed manual. (contributed by [ericbn](https://github.com/ericbn))
* [Mailgun Documentation](https://documentation.mailgun.com) - Email service for developers. Language selector, API code samples, editable in the browser, created with Sphinx. (contributed by [@leemunroe](https://github.com/leemunroe))
* [Grav Documentation](https://learn.getgrav.org) - Documentation for Grav, a modern open source flat-file CMS. Tightly integrated with GitHub in markdown format, with quick search and highlight. (contributed by [@rhuk](https://twitter.com/rhuk))
* [Mailjet API guides](https://dev.mailjet.com/) - Great documentation with generated code samples using Slate from Tripit
* [Atlassian GIT Tutorials](https://www.atlassian.com/git/) - Documentation and tutorials on Git. I like their layout. It is simple and focused on explaining the concepts with good diagrams, tutorials and glossary. (contributed by [@vaseehh](https://twitter.com/vaseehh))
* [Digital Ocean API Docs](https://developers.digitalocean.com/documentation/v2/) - These docs are stellar. Examples are abundant and the organization makes each component of the API easy to reason about. (contributed by [@jasonaibrahim](https://github.com/jasonaibrahim))
* [The LTTng Documentation](https://lttng.org/docs) - The whole documentation of the open source LTTng project on a single page (one page per project release). Features are: sparse style with pleasant colors, good information structure, auto-scrolling navigation, mobile-friendly, dedicated example boxes, glossary, tight integration with the [online man pages](https://lttng.org/man/) of the same version which are rendered with the same style. [Source](https://github.com/lttng/lttng-docs) is written in AsciiDoc (project's man pages too), with custom inline macros for specific features. (contributed by [@eepp](https://eepp.ca/))
* [DocRaptor](https://docraptor.com/documentation) Covers HTML-to-PDF API language wrappers, styling instructions and core API docs.
* [Google Developer Documentation Style Guide](https://developers.google.com/style) - The best style guide I've seen since the Sun Style Guide. I'm agitating to get my team to replace the MMoS with this as the place to look for style guidance that doesn't exist in our team's style guide. (contributed by [@carolinakinetic](https://github.com/carolinakinetic))
* [Go Programming Language Docs](https://golang.org/doc/) - These docs are simple, well-organized, and effective. (contributed by [Ed Bacher](https://github.com/evbacher)).
* **NOT-HTTPS** [Sequelize](http://docs.sequelizejs.com/) - Simple, clear and well-structured docs with a complete Class Reference and listing of all public methods. (contributed by [@bandantonio](https://twitter.com/bandantonio))
* [Vue.js 3.x Docs](https://v3.vuejs.org/guide/introduction.html) - Awesome guide on the Vue.js framework, one of the best docs of any javascript frameworks in my opinion. If you had read them you don't need other manuals on the net to start coding with Vue. (co-contributed by [@flppv](https://github.com/flppv) & [@jinjiang](https://github.com/jinjiang))
* [RStudio Documentation](https://docs.rstudio.com/) - Clean, simple, and easy on the eyes. (contributed by [@foxnic](https://github.com/foxnic))
* [API Blueprint](https://github.com/apiaryio/api-blueprint) Clean, easy to skim. (Contributed by @pharkmillups)
* [Circles and Sines](https://github.com/PharkMillups/beautiful-docs/issues/105) (Contributed by @pharkmillups)

### Writing about Docs 

* [Designing Great API Docs](https://www.pixelstech.net/article/1331352900-Designing-Great-API-Docs) - Blog post by [@jamesyu](https://twitter.com/jamesjyu) about what he/Parse finds essential in API Docs. (contributed by [@hobbyist](https://twitter.com/https://twitter.com/#!/hobbyist))
* [TomDoc](https://tomdoc.org/) - A specification for Ruby library API docs by [@mojombo](https://twitter.com/mojombo) (contributed by [@lenary](https://twitter.com/#!/lenary))
* [Write the Docs](https://conf.writethedocs.org) - A conference for authors of technical documentation. (contributed by [@macintux](https://twitter.com/macintux))
* [Writing Great Documentation](https://jacobian.org/series/great-documentation/) - Covers a variety of topics relating to writing good documentation such as content, style, formatting and so on. (contributed by [Paul A. Wilson](https://github.com/paulalexwilson)). Also check out the [slidedeck](https://www.heavybit.com/wp-content/uploads/2016/04/jacob-kaplan-moss-how-great-documentation-drives-developer-adoption.pdf).

### Generating Docs

* [Doxygen](https://www.doxygen.nl/index.html) - Doxygen is the de facto standard tool for generating documentation from almost all popular programming languages. (contributed by [@nocomplexity](https://github.com/nocomplexity))
* [docco](https://jashkenas.github.io/docco/) - Pretty docs from source code comments with ports for many languages. (contributed by [@kylewest](https://twitter.com/kylewest))
* [DocumentUp](https://documentup.com/jeromegn/documentup) - Instantly beautify your Github repositories' `README.md`. (contributed by [@kylewest](https://twitter.com/kylewest))
* [Sphinx](https://sphinx-doc.org/) - Comprehensive documentation tool using restructuredText with beautiful HTML and PDF output. (contributed by [@nikhilcutshort](https://twitter.com/nikhilcutshort))
* [MkDocs](https://www.mkdocs.org/) - Documentation with Markdown, written in Python. (contributed by [ericbn](https://github.com/ericbn))
* [Read the Docs](https://readthedocs.org/) - Hosted docs using Sphinx or MkDocs, supports translations and finding docs for specific software versions. Used by the Django Docs. (contributed by [Stephen Paulger](https://github.com/stephenpaulger))
* [dr.js](https://github.com/adobe-webplatform/dr.js) - Tiny JavaScript documentation generator from the author of RaphaëlJS.  (contributed by [@nikhilcutshort](https://twitter.com/nikhilcutshort))
* [Markdoc](https://markdoc.org/) - Lightweight documentation/wiki generator in Python, released in the [public domain](https://unlicense.org/). (contributed by [Neelfyn](https://neelfyn.com/))
* **NOT-HTTPS** [ApiGen](http://apigen.org/) - Creates clean API documentation from PHP source code (contributed by [bryceadams](https://bryce.se/))
* [docgenerator](https://github.com/Ralt/docgenerator/blob/master/README.md) - Organize your documentation in Markdown files. (contributed by **NOT-HTTPS** [Florian Margaine](http://margaine.com))
* [dexy](https://www.dexy.it/) - Extensible documentation/report generator supporting multiple programming languages and several input and output formats. (contributed by [troytop](https://github.com/troytop))
* [Slate](https://github.com/tripit/slate) - Static API documentation creation tool from the team at Tripit.
* **NOT-HTTPS** [MireDot](http://www.miredot.com) - REST API documentation generator for Java. Plugs into your build process and generates a searchable html page. (contributed by [bertvh](https://github.com/bertvh))
* [codo](https://github.com/coffeedoc/codo) - CoffeeScript API documentation generator, similar to YARD. (contributed by [Logan Koester](https://github.com/logankoester))
* [Flatdoc](https://ricostacruz.com/flatdoc/) - Create well designed open source documentation from Github repository README files or simple Markdown files. (contributed by [@moore](https://twitter.com/moore))
* [GitBook](https://github.com/GitbookIO/gitbook) - Utility for generating documentation, books and exercises using GitHub/Git and Markdown. (contributed by [Samy Pessé](https://github.com/SamyPesse))
* [Daux](https://github.com/justinwalsh/daux.io) - A documentation generator that uses a simple folder structure and Markdown files to create custom documentation on the fly. It helps you create great looking documentation in a developer friendly way. (contributed by [veshinak](https://github.com/veshinak))
* [comment.js](https://github.com/dciccale/comment.js) - Simple API documentation generator. (contributed by @dciccale - no valid profile link)
* [phpDocumentor](https://www.phpdoc.org/) - phpDocumentor enables you to generate documentation from your PHP source code. (contributed by [shivamdixit](https://shivamdixit.com))
* [Hologram](https://trulia.github.io/hologram/) - Hologram is a Ruby gem that parses comments in your CSS and helps you turn them into a beautiful style guide. (contributed by [@jchild3rs](https://github.com/jchild3rs))
* [Middleman](https://middlemanapp.com/) - Static site generator using all the shortcuts and tools in modern web development. (contributed by [Sota Yamashtia](https://github.com/sotayamashita))
* [documentation.js](https://github.com/documentationjs/documentation) - Generates documentation from JavaScript source code. (contributed by [tmcw](https://github.com/tmcw))
* **NOT-HTTPS** [SassDoc](http://sassdoc.com/) - A Sass documentation generator that utilizes inline comments to make pretty and powerful docs. (contributed by [Hugo Giraudel](https://github.com/HugoGiraudel))
* [Pickles](https://www.picklesdoc.com/#!index.md) - Pickles is an open source living documentation generator that works on feature files written in the Gherkin language.
* [ApiDoc](https://github.com/apidoc/apidoc) RESTful web API Documentation Generator that creates documentation from API descriptions in your source code. (contributed by [Trenton Broughton](https://github.com/trenton42))
* [Documentation theme for Jekyll](https://idratherbewriting.com/documentation-theme-jekyll/) - Documentation theme built on Jekyll. Includes detailed notes on how to tackle nearly every technical documentation scenario, from single sourcing to conditional filtering, PDF output, relative links, and more.
* **NOT-HTTPS** [JSDoc](http://usejsdoc.org/) - Generate JavaScript API documentation directly from source code comments. Also useful as a style guide for JS commenting, in general. Google uses a version of JSDoc tags for its [Closure compiler](https://github.com/google/closure-compiler/wiki/Annotating-JavaScript-for-the-Closure-Compiler).
* [Asciidoctor](https://asciidoctor.org/) - Asciidoctor is a fast text processor and publishing toolchain for converting AsciiDoc content to HTML5, DocBook 5 (or 4.5) and other formats. (contributed by [ThomasG77](https://github.com/ThomasG77))
* [Bookdown](https://bookdown.org/) - A open-source (GPL-3) R package to facilitate writing books and long-form articles/reports with R Markdown. Support for languages other than R, including C/C++, Python, and SQL, etc. (contributed by [ThomasG77](https://github.com/ThomasG77))
* [Pandoc](https://pandoc.org/) If you need to convert files from one markup format into another, pandoc is your swiss-army knife. Can generate documentation from most common markup languages. (contributed by [ThomasG77](https://github.com/ThomasG77))
* [LaTex](https://www.latex-project.org/) Latex is typesetting system that has been around for over 30 yrs and still very popular mostly in academia settings. Its strongest strength is in its capacity and flexibility in creating beautiful mathematical formulas. (contributed by [Tao Li](https://github.com/taolicd)) 
* [gd2md-html](https://github.com/evbacher/gd2md-html/wiki) - gd2md-html is a free Google Docs add-on that converts a formatted Google Doc to a simple, readable Markdown or HTML text file. gd2md-html lets you use Google Docs' editing, formatting, and collaboration tools before you publish to a Markdown or HTML platform. (contributed by [Ed Bacher](https://github.com/evbacher))
* [Documize](https://github.com/documize/community) - One place to author, approve, publish documentation (contributed by [HarveyKandola](https://github.com/HarveyKandola))
* [ESDoc](https://esdoc.org/) - Documentation generator for JavaScript. Similar to [JSDoc](https://usejsdoc.org/), but provides more useful features and stylish look and feel. (contributed by [@bandantonio](https://twitter.com/bandantonio))
* [Ignite](https://github.com/intuit/Ignite) Markdown documentation tool built around react components as first class plugins. Docs generateed using [bulma](https://bulma.io/) (contributed by [hipstersmoothie](https://github.com/ThomasG77))
* [FastAPI](https://fastapi.tiangolo.com) - Python framework for building APIs that automatically generate [Redoc](https://github.com/Redocly/redoc) or [Swagger UI](https://swagger.io) documentation for the REST routes (contributed by [@jrwaine](https://github.com/jrwaine))
