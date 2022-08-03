**Laminas Project** (formerly **Zend Framework** or **ZF**) is an [open
source](open-source_software "wikilink"),
[object-oriented](object-oriented "wikilink") [web application
framework](web_application_framework "wikilink") implemented in [PHP
7](PHP_7 "wikilink") and licensed under the [New BSD
License](New_BSD_License "wikilink").[^1] The framework is basically a
collection of professional [PHP](PHP "wikilink")[^2]-based packages.[^3]
The framework uses various packages by the use of Composer as part of
its package dependency managers; some of them are
[PHPUnit](PHPUnit "wikilink") for testing all packages, Travis CI for
continuous Integration Services. Laminas provides to users a support of
the [model–view–controller](model–view–controller "wikilink") (MVC) in
combination with Front Controller solution.[^4] MVC implementation in
Laminas has five main areas. The [router](Router_(computing) "wikilink")
and dispatcher functions to decide which controller to run based on data
from [URL](Uniform_Resource_Locator "wikilink"), and controller
functions in combination with the model and view to develop and create
the final web page.[^5]

On 17 April 2019 it was announced[^6] that the framework is
transitioning into an open source project hosted by the [Linux
Foundation](Linux_Foundation "wikilink") to be known as Laminas.

## License

Laminas is licensed under the [Open Source
Initiative](Open_Source_Initiative "wikilink") (OSI)-approved [New BSD
License](New_BSD_License "wikilink"). All new contributions are required
to be accompanied with [Developer Certificate of
Origin](Developer_Certificate_of_Origin "wikilink") affirmation.[^7]

Zend Framework also licensed under New BSD License. For ZF1 all code
contributors were required to sign a [Contributor License
Agreement](Contributor_License_Agreement "wikilink") (CLA) based on the
[Apache Software Foundation](Apache_Software_Foundation "wikilink")’s
CLA. The licensing and contribution policies were established to prevent
intellectual property issues for [commercial](Commerce "wikilink") ZF
users, according to Zend's Andi Gutmans.[^8] ZF2 and later is CLA
free.[^9]

## Components and versioning

Starting with Zend Framework version 2.5, components are split into
independently versioned packages and zendframework/zendframework is
converted into a Composer meta-package. Framework components introduced
after the split are not added to the meta-package.

While zendframework/zendframework meta-package release version remains
at 3.0.0, it will instruct Composer to install latest compatible
versions of the framework components, as per the semantic versioning.
Such that zend-mvc component will be installed at its current version
3.1.1, zend-servicemanager at version 3.3.0 and zend-form at version
2.10.2.

Laminas includes following components:[^10]

| Component                     | Description                                                                                                                          |
|-------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| Authentication                | Authenticate users via a variety of adapters, and provide the authenticated identity to your application.                            |
| Barcode                       | Programmatically create and render barcodes as images or in PDFs.                                                                    |
| Cache                         | Caching implementation with a variety of storage options, as well as codified caching strategies for callbacks, classes, and output. |
| Captcha                       | Generate and validate CAPTCHAs using Figlets, images, ReCaptcha, and more.                                                           |
| Code                          | Extensions to the PHP Reflection API, static code scanning, and code generation.                                                     |
| Component Installer           | Composer plugin for injecting modules and configuration providers into application configuration.                                    |
| Config                        | Read and write configuration files.                                                                                                  |
| Config Aggregator             | Aggregate and merge configuration from a variety of sources.                                                                         |
| Console                       | Build console applications using getopt syntax or routing, complete with prompts                                                     |
| Crypt                         | Strong cryptography tools and password hashing.                                                                                      |
| DB                            | Database abstraction layer, SQL abstraction, result set abstraction, and RowDataGateway and TableDataGateway implementations.        |
| Debug                         | Safely dump debug information to HTML.                                                                                               |
| DI                            | Automated dependency injection and instance manager.                                                                                 |
| Diactoros                     | PSR-7 HTTP message implementations.                                                                                                  |
| DOM                           | Query HTML and XML documents using XPath or CSS selectors.                                                                           |
| Escaper                       | Securely and safely escape HTML, HTML attributes, JavaScript, CSS, and URLs.                                                         |
| EventManager                  | Implement events, signal slots, aspects, and observers!                                                                              |
| Expressive                    | PSR-7 middleware in minutes.                                                                                                         |
| Feed                          | Consume and generate Atom and RSS feeds, and interact with Pubsubhubbub.                                                             |
| File                          | Locate PHP classfiles.                                                                                                               |
| Filter                        | Programmatically filter and normalize data and files.                                                                                |
| Form                          | Validate and display simple and complex forms, casting forms to business objects and vice versa.                                     |
| HAL for PSR-7                 | Hypertext Application Language (HAL) for PSR-7.                                                                                      |
| HTTP                          | HTTP message and header abstractions, and HTTP client implementation. (Not a PSR-7 implementation.)                                  |
| Hydrator                      | Serialize objects to arrays, and vice versa.                                                                                         |
| InputFilter                   | Normalize and validate input sets from the web, APIs, the CLI, and more, including files.                                            |
| Internationalization          | Provide translations for your application, and filter and validate internationalized values.                                         |
| JSON                          | De/Serialize JSON in PHP, including JavaScript expressions.                                                                          |
| JSON-RPC Server               | JSON-RPC implementation for PHP.                                                                                                     |
| LDAP                          | Perform LDAP operations, including binding, searching and modifying entries in an LDAP directory.                                    |
| Loader                        | Autoloading and plugin loading strategies.                                                                                           |
| Log                           | Robust, composite logger with filtering, formatting, and PSR-3 support.                                                              |
| Mail                          | Parse, create, store, and send email messages, using a variety of storage and transport protocols.                                   |
| Math                          | Create cryptographically secure pseudo-random numbers, and manage big integers.                                                      |
| Memory                        | Manage data in an environment with limited memory.                                                                                   |
| MIME                          | Create and parse MIME messages and parts.                                                                                            |
| Module Manager                | Modular application system for zend-mvc applications.                                                                                |
| MVC                           | Laminas's event-driven MVC layer, including MVC Applications, Controllers, and Plugins.                                              |
| MVC-Console integration       | Integration between zend-mvc and zend-console.                                                                                       |
| MVC-i18n integration          | Integration between zend-mvc and zend-i18n.                                                                                          |
| fileprg() plugin              | Post/Redirect/Get plugin with file upload handling for zend-mvc controllers.                                                         |
| flashmessenger() plugin       | Plugin for creating and exposing flash messages via zend-mvc controllers.                                                            |
| identity() plugin             | Plugin for retrieving the current authenticated identity within zend-mvc controllers.                                                |
| prg() plugin                  | Post/Redirect/Get plugin for zend-mvc controllers.                                                                                   |
| Navigation                    | Manage trees of pointers to web pages in order to build navigation systems.                                                          |
| Paginator                     | Paginate collections of data from arbitrary sources.                                                                                 |
| ACL                           | Create, manage, and query access control lists.                                                                                      |
| RBAC                          | Provide and query Role-Based Access Controls for your application.                                                                   |
| Problem Details               | PSR-7 Problem Details for HTTP API responses and middleware.                                                                         |
| ProgressBar                   | Create and update progress bars in different environments.                                                                           |
| PSR-7 Bridge                  | PSR-7 \<-\> zend-http message conversions.                                                                                           |
| Router                        | Flexible routing system for HTTP and console applications.                                                                           |
| Serializer                    | Serialize and deserialize PHP structures to a variety of representations.                                                            |
| Server                        | Create Reflection-based RPC servers.                                                                                                 |
| ServiceManager                | Factory-Driven Dependency Injection Container                                                                                        |
| ServiceManager-Di integration | zend-di integration for zend-servicemanager                                                                                          |
| Session                       | Object-oriented interface to PHP sessions and storage.                                                                               |
| SOAP                          | Create, serve, and access SOAP applications, and parse and generate WSDL.                                                            |
| Stdlib                        | SPL extensions, array utilities, error handlers, and more.                                                                           |
| Stratigility                  | PSR-7 middleware foundation for building and dispatching middleware pipelines.                                                       |
| Tag                           | Manipulate and weight taggable items, and create tag clouds.                                                                         |
| Test                          | Tools to facilitate unit testing of zend-mvc applications.                                                                           |
| Text                          | Create FIGlets and text-based tables.                                                                                                |
| URI                           | Object oriented interface to URIs, with facilities for validation.                                                                   |
| Validator                     | Validation classes for a wide range of domains, and the ability to chain validators to create complex validation criteria.           |
| View                          | Flexible view layer supporting and providing multiple view layers, helpers, and more.                                                |
| XML-RPC                       | Fully featured XML-RPC server and client implementations.                                                                            |
| XML2JSON                      | Convert XML documents to JSON.                                                                                                       |

## Installation

Officially supported install method is via
[Composer](Composer_(software) "wikilink") package manager.

Laminas provides meta-package that includes 61 component but recommended
way is to install required framework components individually. Composer
will resolve and install all additional dependencies.

For instance, if you need MVC package, you can install with the
following command:

``` console
$ composer require zendframework/zend-mvc
```

Full list of components is available in Zend Framework
documentation.[^11]

## Anatomy of the framework

Laminas follows configuration-over-convention approach and does not
impose any particular application structure. Skeleton applications for
zend-mvc and zend-expressive are available and provide everything
necessary to run applications and to serve as a good starting point.

## Laminas Project a Series of LF Projects, LLC

Laminas Project is a [nonprofit entity](https://en.wikipedia.org/wiki/Nonprofit_organization)
behind Laminas framework, formed by the [Linux
Foundation](https://en.wikipedia.org/wiki/Linux_Foundation) in 2019 to provide
a vendor-neutral home for the Zend Framework.(ref:
https://www.linuxfoundation.org/blog/lf-forms-laminas-project/)

Zend Framework codebase transitioned to Laminas repositories in january 2020,
marking the official launch of the Laminas Project.
(ref: https://framework.zend.com/blog/2020-01-24-laminas-launch.html)

Laminas Project is governed by a Technical Steering Committee, under a technical charter with the Linux Foundation.

Canonical location of Technical Charter and the list of the TSC members is
under the Laminas Project technical-steering-committee repository on GitHub. https://github.com/laminas/technical-steering-committee

## Sponsor and partners

[Zend Technologies](Zend_Technologies "wikilink"), co-founded by
[PHP](PHP "wikilink") core contributors [Andi
Gutmans](Andi_Gutmans "wikilink") and [Zeev
Suraski](Zeev_Suraski "wikilink"), was the original corporate sponsor of
Zend Framework.[^12] Technology partners include
[IBM](International_Business_Machines "wikilink"),[^13]
[Google](Google "wikilink"),[^14]
[Microsoft](Microsoft "wikilink"),[^15] [Adobe
Systems](Adobe_Systems "wikilink"),[^16] and
[StrikeIron](Strikeiron "wikilink").[^17]

## Features

Laminas features include:[^18]

-   All components are fully object-oriented PHP 5 and are E_STRICT
    compliant, which helps in the development of building tests and
    writing [codes](codes "wikilink") in a bug-free and crash-proof
    application manner.[^19]
-   [Use-at-will](Loose_coupling "wikilink") architecture with loosely
    coupled components and minimal interdependencies
-   Extensible [MVC](Model–view–controller "wikilink") implementation
    supporting layouts and PHP-based templates by default
-   Support for multiple database systems and vendors, including
    [MariaDB](MariaDB "wikilink"), [MySQL](MySQL "wikilink"),
    [Oracle](Oracle_Database "wikilink"), [IBM Db2](IBM_Db2 "wikilink"),
    [Microsoft SQL Server](Microsoft_SQL_Server "wikilink"),
    [PostgreSQL](PostgreSQL "wikilink"), [SQLite](SQLite "wikilink"),
    and [Informix Dynamic Server](Informix_Dynamic_Server "wikilink")
-   Email composition and delivery, retrieval via
    [mbox](mbox "wikilink"), [Maildir](Maildir "wikilink"),
    [POP3](POP3 "wikilink") and [IMAP4](IMAP4 "wikilink")
-   Flexible caching sub-system with support for many types of backends,
    such as [memory](Random_Access_Memory "wikilink") or a [file
    system](file_system "wikilink").
-   With the help of [remote procedure
    call](remote_procedure_call "wikilink") (RPC) and
    REST([Representational State
    Transfer](Representational_State_Transfer "wikilink")) services,
    Zend Apigility helps developers to create APIs, authentication of
    [APIs](Application_programming_interface "wikilink"), documentation
    of APIs, Easy Modification[^20]

## Development of applications

Laminas applications can run on any PHP stack that fulfills the
technical requirements. Zend Technologies provides a PHP stack, [Zend
Server](Zend_Server "wikilink") (or Zend Server Community Edition),
which is advertised to be optimized for running Laminas applications.
Zend Server includes Zend Framework in its installers, along with
[PHP](PHP "wikilink") and all required extensions. According to Zend
Technologies, Zend Server provides improved performance for PHP and
especially Zend Framework applications through opcode acceleration and
several caching capabilities, and includes application monitoring and
diagnostics facilities.[^21] [Zend Studio](Zend_Studio "wikilink") is an
IDE that includes features specifically to integrate with Zend
Framework. It provides an MVC view, MVC code generation based on
Zend_Tool (a component of the Zend Framework), a code formatter, code
completion, parameter assist, and more.[^22] Zend Studio is not free
software, whereas the Zend Framework and Zend Server Community Edition
are free. Zend Server is compatible with common debugging tools such as
[Xdebug](Xdebug "wikilink"). Other developers may want to use a
different PHP stack and another IDE such as [Eclipse
PDT](Eclipse_PDT "wikilink") which works well together with Zend Server.
A pre configured, free version of [Eclipse PDT](Eclipse_PDT "wikilink")
with Zend Debug is available on the Zend web site.

## Code, documentation, and test standards

Code contributions to Laminas are subject to rigorous code,
[documentation](documentation "wikilink"), and test standards. All code
must meet project coding standards and [unit
tests](unit_tests "wikilink") must reach 80% [code
coverage](code_coverage "wikilink") before the corresponding code may be
moved to the release branch.[^23]

## Simple cloud API

On September 22, 2009, [Zend Technologies](Zend_Technologies "wikilink")
announced[^24] that it would be working with technology partners
including [Microsoft](Microsoft "wikilink"), [IBM](IBM "wikilink"),
[Rackspace](Rackspace "wikilink"), [Nirvanix](Nirvanix "wikilink"), and
[GoGrid](GoGrid "wikilink") along with the Zend Framework community to
develop a common API to [cloud](Cloud_computing "wikilink") application
services called the [Simple Cloud API](Simple_Cloud_API "wikilink").
This project is part of Zend Framework and will be hosted on the Zend
Framework website,[^25] but a separate site called simplecloud.org[^26]
has been launched to discuss and download the most current versions of
the API. The Simple Cloud API and several Cloud Services are included in
Zend Framework. The adapters to popular cloud services have reached
production quality.

## Current development

Zend Framework 3.0 was released on June 28, 2016. It includes new
components like a JSON RPC server, a XML to JSON converter, PSR-7
functionality, and compatibility with PHP 7. Zend Framework 3.0 runs up
to 4 times faster than Zend Framework 2, and the packages have been
decoupled to allow for greater reuse.[^27] The contributors of Zend
Framework are actively encouraging the use of Zend Framework version
3.x. The stated end of life for Zend Framework 1 is 2016-09-28, and for
Zend Framework 2 is 2018-03-31. The first development release of Zend
Framework 2.0 was released on August 6, 2010.[^28] Changes made in this
release were the removal of `require_once` statements, migration to PHP
5.3 namespaces, a refactored test suite, a rewritten `Zend\Session`, and
the addition of the new `Zend\Stdlib`. The second development release
was on November 3, 2010.[^29] The first stable release of Zend Framework
2.0 was released 5 September 2012.[^30]

## See also

-   [Comparison of web
    frameworks](Comparison_of_server-side_web_frameworks "wikilink")
-   [New BSD License](New_BSD_License "wikilink")
-   [Zend Server](Zend_Server "wikilink")
-   [Zend Studio](Zend_Studio "wikilink")

## References

## External links

-   

-   [Zend Framework](https://framework.zend.com/)

[Category:Free computer
libraries](Category:Free_computer_libraries "wikilink") [Category:Free
content management
systems](Category:Free_content_management_systems "wikilink")
[Category:PHP frameworks](Category:PHP_frameworks "wikilink")
[Category:Software using the BSD
license](Category:Software_using_the_BSD_license "wikilink")
[Category:Web frameworks](Category:Web_frameworks "wikilink")

[^1]:

[^2]:

[^3]:

[^4]: Supaartagorn, C. (2011). PHP Framework for database management
    based on MVC pattern. *International Journal of Computer Science &
    Information Technology (IJCSIT)*, *3*(2), 251-258.

[^5]:

[^6]:

[^7]:

[^8]:

[^9]:

[^10]:

[^11]:

[^12]:

[^13]:

[^14]:

[^15]:

[^16]:

[^17]:

[^18]:

[^19]: [Why to Use Zend
    Framework?](http://www.suntecoss.com/blog/why-to-use-zend-framework/)
    By SuntecOSS, Retrieved, April 21st, 2016

[^20]: [Zend’s Apigility, an Open Source API Builder for Developing
    Quality
    APIs](http://www.suntecoss.com/blog/zend-apigility-an-open-source-api-builder-for-developing-quality-apis/)
    By SuntecOSS, Retrieved, May 19th, 2016

[^21]:

[^22]:

[^23]:

[^24]:

[^25]:

[^26]: [simplecloud.org](http://www.simplecloud.org)

[^27]:

[^28]:

[^29]:

[^30]:
