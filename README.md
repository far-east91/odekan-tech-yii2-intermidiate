Yii Framework Training by Odekan-Tech
=====================================
We will not follow this guide in ascending order manner. In this training/coaching, we will focus on develop internal system as specified by the client.

[![Our Banner](images/banner.png)](https://www.odekan.my)

This guide or module is exactly the same as the original copy of the documentation. You may refer to the original copy by clicking [here](https://github.com/yiisoft/yii2/tree/master/docs/guide).


What should you have inside your computer?
------------------------------------------
Well, u will need a bunch of software if you want to develop an app. Here's the list:

* [IDE - Netbeans](https://netbeans.org/downloads/)
* [AMP Stack - (Apache, MySQL and PHP)](https://www.mamp.info/en/downloads/)
* [Composer](https://github.com/composer/windows-setup/releases)
* [GIT Client](https://git-scm.com/download/win)

Easy way, click on each link to download.

Before we start
---------------
When we want to create a new software system, we need to plan
thoroughly. In a simple way that we can tell you is to plan an Entity Relationship Diagram. So, in this coaching session, somehow, participator will learn more on designing an ERD. This is how ERD looks like;

![Crows Foot ERD](https://conceptdraw.com/a669c3/p1/preview/640/pict--crow%27s-foot-erd-entity-relationship-diagram-(crow%27s-foot-notation).png--diagram-flowchart-example.png)

Our tentative plan
------------------
|Day|Activity|
|---|--------|
|1  | - Design & Planning<br>- Preparing Yii Skeleton<br>- Designing ERD<br>- Some intro about [amnah extension](https://github.com/amnah/yii2-user) (auth extension) |
|2|Implementation Part 1|
|3|Implementation Part 2|
|4|Implementation Part 3|
|5|- Testing your own software project<br>- How to deploy to server?|

Introduction
------------

* [About Yii](intro-yii.md)
* [Upgrading from Version 1.1](intro-upgrade-from-v1.md)


Getting Started
---------------

* [Installing Yii](start-installation.md)
* [Running Applications](start-workflow.md)
* [Saying Hello](start-hello.md)
* [Working with Forms](start-forms.md)
* [Working with Databases](start-databases.md)
* [Generating Code with Gii](start-gii.md)
* [Looking Ahead](start-looking-ahead.md)


Application Structure
---------------------

* [Overview](structure-overview.md)
* [Entry Scripts](structure-entry-scripts.md)
* [Applications](structure-applications.md)
* [Application Components](structure-application-components.md)
* [Controllers](structure-controllers.md)
* [Models](structure-models.md)
* [Views](structure-views.md)
* [Modules](structure-modules.md)
* [Filters](structure-filters.md)
* [Widgets](structure-widgets.md)
* [Assets](structure-assets.md)
* [Extensions](structure-extensions.md)


Handling Requests
-----------------

* [Overview](runtime-overview.md)
* [Bootstrapping](runtime-bootstrapping.md)
* [Routing and URL Creation](runtime-routing.md)
* [Requests](runtime-requests.md)
* [Responses](runtime-responses.md)
* [Sessions and Cookies](runtime-sessions-cookies.md)
* [Handling Errors](runtime-handling-errors.md)
* [Logging](runtime-logging.md)


Key Concepts
------------

* [Components](concept-components.md)
* [Properties](concept-properties.md)
* [Events](concept-events.md)
* [Behaviors](concept-behaviors.md)
* [Configurations](concept-configurations.md)
* [Aliases](concept-aliases.md)
* [Class Autoloading](concept-autoloading.md)
* [Service Locator](concept-service-locator.md)
* [Dependency Injection Container](concept-di-container.md)


Working with Databases
----------------------

* [Data Access Objects](db-dao.md): Connecting to a database, basic queries, transactions, and schema manipulation
* [Query Builder](db-query-builder.md): Querying the database using a simple abstraction layer
* [Active Record](db-active-record.md): The Active Record ORM, retrieving and manipulating records, and defining relations
* [Migrations](db-migrations.md): Apply version control to your databases in a team development environment
* [Sphinx](https://github.com/yiisoft/yii2-sphinx/blob/master/docs/guide/README.md)
* [Redis](https://github.com/yiisoft/yii2-redis/blob/master/docs/guide/README.md)
* [MongoDB](https://github.com/yiisoft/yii2-mongodb/blob/master/docs/guide/README.md)
* [ElasticSearch](https://github.com/yiisoft/yii2-elasticsearch/blob/master/docs/guide/README.md)


Getting Data from Users
-----------------------

* [Creating Forms](input-forms.md)
* [Validating Input](input-validation.md)
* [Uploading Files](input-file-upload.md)
* [Collecting Tabular Input](input-tabular-input.md)
* [Getting Data for Multiple Models](input-multiple-models.md)


Displaying Data
---------------

* [Data Formatting](output-formatting.md)
* [Pagination](output-pagination.md)
* [Sorting](output-sorting.md)
* [Data Providers](output-data-providers.md)
* [Data Widgets](output-data-widgets.md)
* [Working with Client Scripts](output-client-scripts.md)
* [Theming](output-theming.md)


Security
--------

* [Overview](security-overview.md)
* [Authentication](security-authentication.md)
* [Authorization](security-authorization.md)
* [Working with Passwords](security-passwords.md)
* [Cryptography](security-cryptography.md)
* [Auth Clients](https://github.com/yiisoft/yii2-authclient/blob/master/docs/guide/README.md)
* [Best Practices](security-best-practices.md)


Caching
-------

* [Overview](caching-overview.md)
* [Data Caching](caching-data.md)
* [Fragment Caching](caching-fragment.md)
* [Page Caching](caching-page.md)
* [HTTP Caching](caching-http.md)


RESTful Web Services
--------------------

* [Quick Start](rest-quick-start.md)
* [Resources](rest-resources.md)
* [Controllers](rest-controllers.md)
* [Routing](rest-routing.md)
* [Response Formatting](rest-response-formatting.md)
* [Authentication](rest-authentication.md)
* [Rate Limiting](rest-rate-limiting.md)
* [Versioning](rest-versioning.md)
* [Error Handling](rest-error-handling.md)


Development Tools
-----------------

* [Debug Toolbar and Debugger](https://github.com/yiisoft/yii2-debug/blob/master/docs/guide/README.md)
* [Generating Code using Gii](https://github.com/yiisoft/yii2-gii/blob/master/docs/guide/README.md)
* [Generating API Documentation](https://github.com/yiisoft/yii2-apidoc)


Testing
-------

* [Overview](test-overview.md)
* [Testing environment setup](test-environment-setup.md)
* [Unit Tests](test-unit.md)
* [Functional Tests](test-functional.md)
* [Acceptance Tests](test-acceptance.md)
* [Fixtures](test-fixtures.md)


Special Topics
--------------

* [Advanced Project Template](https://github.com/yiisoft/yii2-app-advanced/blob/master/docs/guide/README.md)
* [Building Application from Scratch](tutorial-start-from-scratch.md)
* [Console Commands](tutorial-console.md)
* [Core Validators](tutorial-core-validators.md)
* [Internationalization](tutorial-i18n.md)
* [Mailing](tutorial-mailing.md)
* [Performance Tuning](tutorial-performance-tuning.md)
* [Shared Hosting Environment](tutorial-shared-hosting.md)
* [Template Engines](tutorial-template-engines.md)
* [Working with Third-Party Code](tutorial-yii-integration.md)


Widgets
-------

* [GridView](http://www.yiiframework.com/doc-2.0/yii-grid-gridview.html)
* [ListView](http://www.yiiframework.com/doc-2.0/yii-widgets-listview.html)
* [DetailView](http://www.yiiframework.com/doc-2.0/yii-widgets-detailview.html)
* [ActiveForm](http://www.yiiframework.com/doc-2.0/guide-input-forms.html#activerecord-based-forms-activeform)
* [Pjax](http://www.yiiframework.com/doc-2.0/yii-widgets-pjax.html)
* [Menu](http://www.yiiframework.com/doc-2.0/yii-widgets-menu.html)
* [LinkPager](http://www.yiiframework.com/doc-2.0/yii-widgets-linkpager.html)
* [LinkSorter](http://www.yiiframework.com/doc-2.0/yii-widgets-linksorter.html)
* [Bootstrap Widgets](https://github.com/yiisoft/yii2-bootstrap/blob/master/docs/guide/README.md)
* [jQuery UI Widgets](https://github.com/yiisoft/yii2-jui/blob/master/docs/guide/README.md)


Helpers
-------

* [Overview](helper-overview.md)
* [ArrayHelper](helper-array.md)
* [Html](helper-html.md)
* [Url](helper-url.md)

"# odekan-tech-yii2-intermidiate" 
