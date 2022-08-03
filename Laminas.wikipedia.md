{{Distinguish|Zend Engine}}
{{cleanup rewrite|date=April 2017}}
{{Infobox software
| name = Laminas Project
| logo = ZendFramework-Logo.png
| author = [[Zend Technologies]]
| developer = [[Linux Foundation]]
| released = {{Start date and age|2006|03|03}}<ref>{{cite web |url=http://framework.zend.com/downloads/archives |title=Archives |website=Zend Framework |access-date=May 1, 2013}}</ref>
| latest release version = <!-- If you update this, remember to also update [[Comparison of web application frameworks]]-->3.0.0<ref name="zend_release">{{cite web|url=https://github.com/zendframework/zendframework/blob/master/CHANGELOG.md|title=zendframework/zendframework|website=GitHub|access-date=May 17, 2017}}</ref>
| latest release date = {{Start date and age|2016|6|28}}
| latest preview version = <!--2.2.0rc1-->
| latest preview date = <!--{{Start date and age|2013|05|01}}<ref>{{cite web |url=http://framework.zend.com/blog/zend-framework-2-2-0rc1-released.html |title=Zend Framework 2.2.0rc1 Released! |last=Weier O'Phinney |first=Matthew |date=May 1, 2013 |website=ZF Blog |access-date=May 1, 2013 }}</ref>-->
| repo = {{URL|https://github.com/zendframework/zendframework|Zend Repository}}
| programming language = [[PHP 7]]
| operating system = [[Cross-platform]]
| license = [[New BSD license]]
| website = {{Official URL}}
}}

'''Laminas Project''' (formerly '''Zend Framework''' or '''ZF''') is an [[open-source software|open source]], [[object-oriented]] [[web application framework]] implemented in [[PHP 7]] and licensed under the [[New BSD License]].<ref name="zf_overview">{{cite web | url=http://framework.zend.com/manual/en/introduction.html | access-date=2009-02-12 | title=Introduction to Zend Framework | work=ZF Programmer's Reference Guide | archive-date=2009-02-11 | archive-url=https://web.archive.org/web/20090211210131/http://framework.zend.com/manual/en/introduction.html | url-status=dead }}</ref> The framework is basically a collection of professional [[PHP]]<ref>{{Cite web|url=https://www.w3schools.com/php/|title=PHP 5 Tutorial|website=www.w3schools.com|language=en-US|access-date=2017-02-20}}</ref>-based packages.<ref name=":1"/> The framework uses various packages by the use of Composer as part of its package dependency managers; some of them are [[PHPUnit]] for testing all packages, Travis CI for continuous Integration Services. Laminas provides to users a support of the [[model–view–controller]] (MVC) in combination with Front Controller solution.<ref name=":0">Supaartagorn, C. (2011). PHP Framework for database management based on MVC pattern. ''International Journal of Computer Science & Information Technology (IJCSIT)'', ''3''(2), 251-258.</ref> MVC implementation in Laminas has five main areas. The [[Router (computing)|router]] and dispatcher functions to decide which controller to run based on data from [[Uniform Resource Locator|URL]], and controller functions in combination with the model and view to develop and create the final web page.<ref name=":1">{{Cite web|url=https://framework.zend.com/about|title=Zend Framework - About|last=Company|first=Zend, a Rogue Wave|website=framework.zend.com|access-date=2017-02-05}}</ref>

On 17 April 2019 it was announced<ref>{{cite web|url=https://framework.zend.com/blog/2019-04-17-announcing-laminas.html|title=From Zend to Laminas|date=17 April 2019}}</ref> that the framework is transitioning into an open source project hosted by the [[Linux Foundation]] to be known as Laminas.

==License==
Laminas is licensed under the [[Open Source Initiative]] (OSI)-approved [[New BSD License]]. All new contributions are required to be accompanied with [[Developer Certificate of Origin]] affirmation.<ref>{{cite_web |url=https://github.com/laminas/technical-steering-committee/blob/main/CHARTER.md| title=Technical Charter (the "Charter") for Laminas Project a Series of LF Projects, LLC.}}</ref>

Zend Framework also licensed under New BSD License. For ZF1 all code contributors were required to sign a [[Contributor License Agreement]] (CLA) based on the [[Apache Software Foundation]]’s CLA. The licensing and contribution policies were established to prevent intellectual property issues for [[Commerce|commercial]] ZF users, according to Zend's Andi Gutmans.<ref>{{cite web | last=Gutmans | first=Andi | title=Zend Framework (post is too long so make sure to grab coffee) | date=2005-10-27 | url=http://andigutmans.blogspot.com/2005_10_01_archive.html | work=Andi on Web & IT | access-date=2009-02-11}}</ref> ZF2 and later is CLA free.<ref>{{cite web | url=http://framework.zend.com/participate/contributor-guide-v1 | title=Contributor Guide (ZF v1)}}</ref>

==Components and versioning==
Starting with Zend Framework version 2.5, components are split into independently versioned packages and zendframework/zendframework is converted into a Composer meta-package. Framework components introduced after the split are not added to the meta-package.

While zendframework/zendframework meta-package release version remains at 3.0.0, it will instruct Composer to install latest compatible versions of the framework components, as per the semantic versioning. Such that zend-mvc component will be installed at its current version 3.1.1, zend-servicemanager at version 3.3.0 and zend-form at version 2.10.2.

Laminas includes following components:<ref name=":3">{{Cite web|url=https://docs.zendframework.com/|title=Documentation for the ZF components}}</ref>

{| class="wikitable"
! Component
! Description
|-
|Authentication
|Authenticate users via a variety of adapters, and provide the authenticated identity to your application.
|-
|Barcode
|Programmatically create and render barcodes as images or in PDFs.
|-
|Cache
|Caching implementation with a variety of storage options, as well as codified caching strategies for callbacks, classes, and output.
|-
|Captcha
|Generate and validate CAPTCHAs using Figlets, images, ReCaptcha, and more.
|-
|Code
|Extensions to the PHP Reflection API, static code scanning, and code generation.
|-
|Component Installer
|Composer plugin for injecting modules and configuration providers into application configuration.
|-
|Config
|Read and write configuration files.
|-
|Config Aggregator
|Aggregate and merge configuration from a variety of sources.
|-
|Console
|Build console applications using getopt syntax or routing, complete with prompts
|-
|Crypt
|Strong cryptography tools and password hashing.
|-
|DB
|Database abstraction layer, SQL abstraction, result set abstraction, and RowDataGateway and TableDataGateway implementations.
|-
|Debug
|Safely dump debug information to HTML.
|-
|DI
|Automated dependency injection and instance manager.
|-
|Diactoros
|PSR-7 HTTP message implementations.
|-
|DOM
|Query HTML and XML documents using XPath or CSS selectors.
|-
|Escaper
|Securely and safely escape HTML, HTML attributes, JavaScript, CSS, and URLs.
|-
|EventManager
|Implement events, signal slots, aspects, and observers!
|-
|Expressive
|PSR-7 middleware in minutes.
|-
|Feed
|Consume and generate Atom and RSS feeds, and interact with Pubsubhubbub.
|-
|File
|Locate PHP classfiles.
|-
|Filter
|Programmatically filter and normalize data and files.
|-
|Form
|Validate and display simple and complex forms, casting forms to business objects and vice versa.
|-
|HAL for PSR-7
|Hypertext Application Language (HAL) for PSR-7.
|-
|HTTP
|HTTP message and header abstractions, and HTTP client implementation.  (Not a PSR-7 implementation.)
|-
|Hydrator
|Serialize objects to arrays, and vice versa.
|-
|InputFilter
|Normalize and validate input sets from the web, APIs, the CLI, and more, including files.
|-
|Internationalization
|Provide translations for your application, and filter and validate internationalized values.
|-
|JSON
|De/Serialize JSON in PHP, including JavaScript expressions.
|-
|JSON-RPC Server
|JSON-RPC implementation for PHP.
|-
|LDAP
|Perform LDAP operations, including binding, searching and modifying entries in an LDAP directory.
|-
|Loader
|Autoloading and plugin loading strategies.
|-
|Log
|Robust, composite logger with filtering, formatting, and PSR-3 support.
|-
|Mail
|Parse, create, store, and send email messages, using a variety of storage and transport protocols.
|-
|Math
|Create cryptographically secure pseudo-random numbers, and manage big integers.
|-
|Memory
|Manage data in an environment with limited memory.
|-
|MIME
|Create and parse MIME messages and parts.
|-
|Module Manager
|Modular application system for zend-mvc applications.
|-
|MVC
|Laminas's event-driven MVC layer, including MVC Applications, Controllers, and Plugins.
|-
|MVC-Console integration
|Integration between zend-mvc and zend-console.
|-
|MVC-i18n integration
|Integration between zend-mvc and zend-i18n.
|-
|fileprg() plugin
|Post/Redirect/Get plugin with file upload handling for zend-mvc controllers.
|-
|flashmessenger() plugin
|Plugin for creating and exposing flash messages via zend-mvc controllers.
|-
|identity() plugin
|Plugin for retrieving the current authenticated identity within zend-mvc controllers.
|-
|prg() plugin
|Post/Redirect/Get plugin for zend-mvc controllers.
|-
|Navigation
|Manage trees of pointers to web pages in order to build navigation systems.
|-
|Paginator
|Paginate collections of data from arbitrary sources.
|-
|ACL
|Create, manage, and query access control lists.
|-
|RBAC
|Provide and query Role-Based Access Controls for your application.
|-
|Problem Details
|PSR-7 Problem Details for HTTP API responses and middleware.
|-
|ProgressBar
|Create and update progress bars in different environments.
|-
|PSR-7 Bridge
|PSR-7 <-> zend-http message conversions.
|-
|Router
|Flexible routing system for HTTP and console applications.
|-
|Serializer
|Serialize and deserialize PHP structures to a variety of representations.
|-
|Server
|Create Reflection-based RPC servers.
|-
|ServiceManager
|Factory-Driven Dependency Injection Container
|-
|ServiceManager-Di integration
|zend-di integration for zend-servicemanager
|-
|Session
|Object-oriented interface to PHP sessions and storage.
|-
|SOAP
|Create, serve, and access SOAP applications, and parse and generate WSDL.
|-
|Stdlib
|SPL extensions, array utilities, error handlers, and more.
|-
|Stratigility
|PSR-7 middleware foundation for building and dispatching middleware pipelines.
|-
|Tag
|Manipulate and weight taggable items, and create tag clouds.
|-
|Test
|Tools to facilitate unit testing of zend-mvc applications.
|-
|Text
|Create FIGlets and text-based tables.
|-
|URI
|Object oriented interface to URIs, with facilities for validation.
|-
|Validator
|Validation classes for a wide range of domains, and the ability to chain validators to create complex validation criteria.
|-
|View
|Flexible view layer supporting and providing multiple view layers, helpers, and more.
|-
|XML-RPC
|Fully featured XML-RPC server and client implementations.
|-
|XML2JSON
|Convert XML documents to JSON.
|}

== Installation ==
Officially supported install method is via [[Composer (software)|Composer]] package manager.

Laminas provides meta-package that includes 61 component but recommended way is to install required framework components individually. Composer will resolve and install all additional dependencies.

For instance, if you need MVC package, you can install with the following command:<syntaxhighlight lang="console">
$ composer require zendframework/zend-mvc

</syntaxhighlight>Full list of components is available in Zend Framework documentation.<ref name=":3" />

==Anatomy of the framework==
Laminas follows configuration-over-convention approach and does not impose any particular application structure. Skeleton applications for zend-mvc and zend-expressive are available and provide everything necessary to run applications and to serve as a good starting point.

==Sponsor and partners==
[[Zend Technologies]], co-founded by [[PHP]] core contributors [[Andi Gutmans]] and [[Zeev Suraski]], was the original corporate sponsor of Zend Framework.<ref name="history">{{cite web|access-date=2009-02-11|url=http://www.php.net/history|title=History of PHP and related projects |publisher=The PHP Group }}</ref> Technology partners include [[International Business Machines|IBM]],<ref name="ibm_partner">{{cite news | last=LaMonica | first=Martin | title=IBM backs open-source Web software | url=http://news.cnet.com/IBM-backs-open-source-Web-software/2100-7344_3-5589559.html?tag=nw.14 | access-date=2009-02-11 | work=cnet.com | date=2005-02-25}}</ref> [[Google]],<ref name="google_partner">{{cite web | last=Kernel | first=Sean Michael | title=Google Data Joins PHP Zend Framework | url=http://www.internetnews.com/dev-news/article.php/3650066 | access-date=2009-02-11 | work=internetnews.com | date=2006-12-20}}</ref> [[Microsoft]],<ref name="ms_partner">{{cite web | last=Krill | first=Paul | title=Microsoft, Zend boost PHP for Windows | url=http://www.infoworld.com/article/06/10/31/HNzenphp_1.html | access-date=2009-02-11 | work=infoworld.com | date=2006-10-31}}</ref> [[Adobe Systems]],<ref name="adobe_partner">{{cite web | last=Potter | first=Mike | title=Adobe Contributing AMF Support to Zend Framework | access-date=2009-02-11 | url=http://blogs.adobe.com/flex/archives/2008/07/adobe_contributing_amf_support.html | archive-url=https://web.archive.org/web/20090207073623/http://blogs.adobe.com/flex/archives/2008/07/adobe_contributing_amf_support.html | url-status=dead | archive-date=2009-02-07 | date=2014-05-21 | work=The Official Flex Team Blog}}</ref> and [[Strikeiron|StrikeIron]].<ref>{{cite web | url=http://www.strikeiron.com/partners/featured_partners.aspx | title=StrikeIron Featured Partners | access-date=2009-02-11}}</ref>

==Features==
Laminas features include:<ref name="Zend_overview">{{cite web | title=About Zend Framework | url=http://framework.zend.com/about/overview | access-date=2009-02-11 | archive-date=2009-02-11 | archive-url=https://web.archive.org/web/20090211210958/http://framework.zend.com/about/overview | url-status=dead }}</ref>
* All components are fully object-oriented PHP 5 and are E_STRICT compliant, which helps in the development of building tests and writing [[codes]] in a bug-free and crash-proof application manner.<ref>[http://www.suntecoss.com/blog/why-to-use-zend-framework/ Why to Use Zend Framework?] By SuntecOSS, Retrieved, April 21st, 2016</ref>
* [[Loose coupling|Use-at-will]] architecture with loosely coupled components and minimal interdependencies
* Extensible [[Model–view–controller|MVC]] implementation supporting layouts and PHP-based templates by default
* Support for multiple database systems and vendors, including [[MariaDB]], [[MySQL]], [[Oracle Database|Oracle]], [[IBM Db2]], [[Microsoft SQL Server]], [[PostgreSQL]], [[SQLite]], and [[Informix Dynamic Server]]
* Email composition and delivery, retrieval via [[mbox]], [[Maildir]], [[POP3]] and [[IMAP4]]
* Flexible caching sub-system with support for many types of backends, such as [[Random Access Memory|memory]] or a [[file system]].
* With the help of [[remote procedure call]] (RPC) and REST([[Representational State Transfer]]) services, Zend Apigility helps developers to create APIs, authentication of [[Application programming interface|APIs]], documentation of APIs, Easy Modification<ref>[http://www.suntecoss.com/blog/zend-apigility-an-open-source-api-builder-for-developing-quality-apis/ Zend’s Apigility, an Open Source API Builder for Developing Quality APIs] By SuntecOSS, Retrieved, May 19th, 2016</ref>

==Development of applications==
Laminas applications can run on any PHP stack that fulfills the technical requirements. Zend Technologies provides a PHP stack, [[Zend Server]] (or Zend Server Community Edition), which is advertised to be optimized for running Laminas applications. Zend Server includes Zend Framework in its installers, along with [[PHP]] and all required extensions. According to Zend Technologies, Zend Server provides improved performance for PHP and especially Zend Framework applications through opcode acceleration and several caching capabilities, and includes application monitoring and diagnostics facilities.<ref>{{cite web|url=http://www.zend.com/products/server|title=Zend site|website=Zend.com|access-date=May 17, 2017}}</ref> [[Zend Studio]] is an IDE that includes features specifically to integrate with Zend Framework. It provides an MVC view, MVC code generation based on Zend_Tool (a component of the Zend Framework), a code formatter, code completion, parameter assist, and more.<ref>{{cite web|url=http://www.zend.com/en/products/studio/features#ZFI|title=Download Zend Studio - IDE, PHP profiler, mobile, unit testing & more|website=www.Zend.com|access-date=May 17, 2017|archive-date=June 1, 2017|archive-url=https://web.archive.org/web/20170601031116/http://www.zend.com/en/products/studio/features#ZFI|url-status=dead}}</ref> Zend Studio is not free software, whereas the Zend Framework and Zend Server Community Edition are free. Zend Server is compatible with common debugging tools such as [[Xdebug]]. Other developers may want to use a different PHP stack and another IDE such as [[Eclipse PDT]] which works well together with Zend Server. A pre configured, free version of [[Eclipse PDT]] with Zend Debug is available on the Zend web site.

==Code, documentation, and test standards==
Code contributions to Laminas are subject to rigorous code, [[documentation]], and test standards. All code must meet project coding standards and [[unit tests]] must reach 80% [[code coverage]] before the corresponding code may be moved to the release branch.<ref name="Contributor-Guide">{{cite web
| date = July 1, 2006
| title = Zend Framework Contributor Guide
| url = http://framework.zend.com/wiki/display/ZFDEV/Zend+Framework+Contributor+Guide
| access-date = July 14, 2008
| archive-date = May 18, 2008
| archive-url = https://web.archive.org/web/20080518095823/http://framework.zend.com/wiki/display/ZFDEV/Zend+Framework+Contributor+Guide
| url-status = dead
}}</ref>

==Simple cloud API==
On September 22, 2009, [[Zend Technologies]] announced<ref name="SimpleCloud_announcement">{{cite web|title=Simple Cloud API Press Release |url=http://www.zend.com/en/company/news/press/zend-teams-with-ibm-microsoft-rackspace-and-other-cloud-leaders-on-open-source-initiative-to-drive-cloud-application-development |access-date=2009-11-05 |url-status=dead |archive-url=https://web.archive.org/web/20091201014623/http://www.zend.com/en/company/news/press/zend-teams-with-ibm-microsoft-rackspace-and-other-cloud-leaders-on-open-source-initiative-to-drive-cloud-application-development |archive-date=December 1, 2009 }}</ref>  that it would be working with technology partners including [[Microsoft]], [[IBM]], [[Rackspace]], [[Nirvanix]], and [[GoGrid]] along with the Zend Framework community to develop a common API to [[Cloud computing|cloud]] application services called the [[Simple Cloud API]]. This project is part of Zend Framework and will be hosted on the Zend Framework website,<ref name="Zend_website">{{cite web | title=Zend Framework website | url=http://framework.zend.com/ | access-date=2009-11-05}}</ref> but a separate site called simplecloud.org<ref>[http://www.simplecloud.org simplecloud.org]</ref> has been launched to discuss and download the most current versions of the API. The Simple Cloud API and several Cloud Services are included in Zend Framework. The adapters to popular cloud services have reached production quality.

==Current development==
Zend Framework 3.0 was released on June 28, 2016. It includes new components like a JSON RPC server, a XML to JSON converter, PSR-7 functionality, and compatibility with PHP 7.  Zend Framework 3.0 runs up to 4 times faster than Zend Framework 2, and the packages have been decoupled to allow for greater reuse.<ref>{{cite web|author=zendframework |url=https://framework.zend.com/blog/2016-06-28-zend-framework-3.html |title=Zend Framework 3 Released!|date=2016-06-28|access-date=2016-10-12}}</ref> The contributors of Zend Framework are actively encouraging the use of Zend Framework version 3.x. The stated end of life for Zend Framework 1 is 2016-09-28, and for Zend Framework 2 is 2018-03-31. The first development release of Zend Framework 2.0 was released on August 6, 2010.<ref name="Zend_2.0.0.dev1">{{cite web | title=Zend Framework 2.0.0dev1 | url=http://devzone.zend.com/article/12385-First-Development-Milestone-of-ZF-2.0-Released | date=2010-08-06 | access-date=2010-09-04}}</ref> Changes made in this release were the removal of <code>require_once</code> statements, migration to PHP 5.3 namespaces, a refactored test suite, a rewritten <code>Zend\Session</code>, and the addition of the new <code>Zend\Stdlib</code>. The second development release was on November 3, 2010.<ref name="Zend_2.0.0.dev2">{{cite web | title=Zend Framework 2.0.0dev2 | url=http://framework.zend.com/announcements/2010-11-03-zf2dev2 | date=2011-11-03 | access-date=2011-03-18 | archive-date=2011-07-16 | archive-url=https://web.archive.org/web/20110716095940/http://framework.zend.com/announcements/2010-11-03-zf2dev2 | url-status=dead }}</ref> The first stable release of Zend Framework 2.0 was released 5 September 2012.<ref>{{cite web|url=http://framework.zend.com/blog/zend-framework-2-0-0-stable-released.html |title=Zend Framework 2.0.0 STABLE Released! - Zend Framework - Zend Framework |publisher=Framework.zend.com |date=September 5, 2012 |access-date=June 14, 2013}}</ref>

== See also ==
{{Portal|Free and open-source software}}
* [[Comparison of server-side web frameworks|Comparison of web frameworks]]
* [[New BSD License]]
* [[Zend Server]]
* [[Zend Studio]]

==References==
{{Reflist|2}}

==External links==
*{{Official website}}
*[https://framework.zend.com/ Zend Framework]

{{PHP}}
{{Application frameworks}}

{{Authority control}}

[[Category:Free computer libraries]]
[[Category:Free content management systems]]
[[Category:PHP frameworks]]
[[Category:Software using the BSD license]]
[[Category:Web frameworks]]
