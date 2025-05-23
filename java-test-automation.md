# Java test automation

A comprehensive curated list of Java test automation frameworks, tools, libraries and software to help software engineers easily bootstrap test automation on Java. Sponsored by http://sdclabs.com

[![Have questions\issues\problems, join the chat at https://gitter.im/atinfo/awesome-test-automation](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/atinfo/awesome-test-automation)

Table of content:

- [xUnit frameworks](#xunit-frameworks)
- [TDD \ ATTD \ BDD](#tdd--atdd--bdd)
- [Model-Based Testing](#model-based-testing)
- [Code Analysis and Coverage](#code-analysis-and-coverage)
- [Web UI test automation](#web-ui-test-automation)
- [Mobile test automation](#mobile-test-automation)
- [API test automation](#api-test-automation)
- [Windows UI test automation](#windows-ui-test-automation)
- [Unix \ Linux UI test automation](#unix--linux-ui-test-automation)
- [MacOS UI test automation](#macos-ui-test-automation)
- [Server side test automation](#server-side-test-automation)
- [Virtual environments](#virtual-environments)
- [Performance & stress & load](#performance--stress--load)
- [Security checking](#security-checking)
- [Build Tools](#build-tools)
- [Continuous Integration](#continuous-integration)
- [Reporting](#reporting)
- [Documentation generation](#documentation-generation)
- [Editors, IDE and consoles](#editors-ide-consoles)
- [ORM frameworks and libraries](#orm-frameworks-and-libraries)
- [Useful libs](#useful-libs)
- [Test Data](#test-data)
- [DataBase test automation](#database-test-automation)

Also:

- [Resources](#resources)
- [Other Awesome Test Automation Lists](#other-awesome-test-automation-lists)
- [Contributing](#contributing)

---

## xUnit frameworks

* [JUnit](http://junit.org/) - Common testing framework.
* [TestNG](http://testng.org/) - TestNG - Testing framework.
    * [Test Data Supplier](https://github.com/sskorol/test-data-supplier) - TestNG DataProvider wrapper which helps to supply test data in a more flexible way.
* [Sunshine](https://github.com/tatools/sunshine/) - Sunshine is a wrapper on Java xUnit test runners (such as TestNG, Junit...) which allows automatically find classes with tests within the jar file, passes them to desired test runner and reports an execution status.


## TDD \ ATDD \ BDD

- tools
    * [JBehave](http://jbehave.org/) - A framework for Behaviour-Driven Development (BDD). BDD is an evolution of test-driven development (TDD) and acceptance-test driven design, and is intended to make these practices more accessible and intuitive to newcomers and experts alike.
    * [Cucumber-JVM](https://github.com/cucumber/cucumber-jvm) - A pure Java implementation of Cucumber that supports the most popular programming languages for the JVM.
    * [JGiven](https://github.com/TNG/JGiven) - A developer-friendly and pragmatic BDD tool for Java. Developers write scenarios in plain Java using a fluent, domain-specific API, JGiven generates reports that are readable by domain experts.
    * [easyb](http://easyb.org/) - A behavior driven development framework for the Java platform. By using a specification based Domain Specific Language, easyb aims to enable executable, yet readable documentation.
    * [Robot Framework](http://robotframework.org/) - A generic test automation framework for acceptance testing and acceptance test-driven development (ATDD).
        * [awesome-robotframework](https://github.com/fkromer/awesome-robotframework) - A curated list of awesome Robot Framework resources and libraries
    * [Spectrum](https://github.com/greghaskins/spectrum) - A BDD-style test runner for Java 8. Inspired by Jasmine, RSpec, and Cucumber.
    * [Gauge](https://gauge.org/) - Gauge is a light-weight cross-platform test automation tool with the ability to author test cases in the business language.
    * [Spock](http://spockframework.org/) - Specification testing framework for Java and Groovy.
    * [Concordion](https://concordion.org/) - Flexible, extensible BDD/SBE tool that creates beautiful living documentation using business language
- extensions
    * [cucumber-report-db](https://github.com/porscheinformatik/cucumber-report-db) - Stores results of BDD tests with Cucumber-JVM in a database and provides reporting capabilities.

## Model-Based Testing

- [GraphWalker](http://graphwalker.org/) - A framework for Model-Based Testing. The tool reads models in various formats like graphml, dot or json, and then generates tests from the models.

## Code analysis and coverage

* [SonarQube](http://www.sonarqube.org) - Open source project to manage code quality.
* [Gradle Quality Plugin](https://github.com/xvik/gradle-quality-plugin) - Static code analysis for Java and Groovy projects using Checkstyle, PMD, FindBugs and CodeNarc. Plugin implements unified console output for all quality plugins which greatly simplifies developer workflow: only console is required for working with violations and makes it feel the same as java compiler errors.
* [Qulice](https://github.com/teamed/qulice) - Qulice is a static analysis quality control instrument for Java projects. It combines all the best static analysis instruments and pre-configure them. You don't need to use and configure them individually any more.
* [JaCoCo](https://github.com/jacoco/jacoco) - JaCoCo is a free code coverage library for Java, which has been created by the EclEmma team based on the lessons learned from using and integration existing libraries for many years.

## Web UI test automation

- libraries
    * [Selenium](http://docs.seleniumhq.org/) - Portable software testing framework for web applications.
    * [SikuliX](http://www.sikulix.com/) - SikuliX automates anything you see on the screen of your desktop computer running Windows, Mac or some Linux/Unix. It uses image recognition powered by OpenCV to identify and control GUI components. This is handy in cases when there is no easy access to a GUI's internals or the source code of the application or web page you want to act on.
- frameworks and wrappers
    * [Selenide](http://selenide.org/) - Concise API around Selenium to write stable and readable UI tests.
    * [Selenified](https://github.com/Coveros/selenified) - An open source framework to simplify Selenium Testing. It provides a wrapper for Selenium calls to add detailed reporting, error handling, simple test setup in a thread-safe manner, and can run either locally or in the cloud (Grid or SauceLabs).
    * [Serenity BDD (Thucydides)](http://www.thucydides.info/) - An innovative open source library that helps you write more effective automated acceptance tests, and uses these acceptance tests to generates rich documentation and reports about your product and project.
    * [htmlelements](https://github.com/yandex-qatools/htmlelements) - A Java framework providing easy-to-use way of interaction with web-page elements in web-page tests.
    * [atlassian-selenium](https://bitbucket.org/atlassian/atlassian-selenium) - An open-source (BSD) project that aims at facilitating development of functional tests in Selenium/WebDriver libraries.
    * [stevia](https://github.com/persado/stevia) - Open Source QA Automation Testing Framework by Persado
    * [darcy](https://github.com/darcy-framework) - An open source Java 8 framework for modeling user interfaces as page objects with a declarative, automation-library-agnostic DSL
    * [Satisfy](https://tapack.github.io/satisfy/) - An open source Java framework based on Thucydides + Jbehave. Supports to work with WebUI, SOAP, REST, emails, files and generate random data out of the box.
    * [JDI Light](https://github.com/jdi-testing/jdi-light) - is the test Framework for UI test automation that helps to makes your tests fast and sustainable and provide obvious and predictable test run result.
    * [Geb Framework](http://gebish.org/) - A groovy test automation framework designed for the use with the Webdriver Page Object model and the Spock Framework for (BDD).
    * [FluentLenium](https://github.com/FluentLenium/FluentLenium) - FluentLenium helps you writing readable, reusable, reliable and resilient UI functional tests for the browser. FluentLenium provides a Java fluent interface to Selenium, and brings some magic to avoid common issues faced by Selenium users.
    * [Selion](https://github.com/paypal/SeLion) - builds on top of TestNG and Selenium to provide a set of capabilities that get you up and running with WebDriver in a short time. It can be used for testing web and mobile applications.
    * [Frameworkium](https://frameworkium.github.io/) - automation framework for web, app, and API testing. Integrates: saucelabs, allure, rest-assured, jackson, gson. Published on Jitpack repository. 
    * [Carina](https://carina-core.io) - Carina is a Java-based test automation framework that unites all testing layers: Mobile applications (web, native, hybrid), WEB applications, REST services, Databases.
    * [NoraUi](https://noraui.github.io/#) - NoraUi, for NOn-Regression Automation for User Interfaces, is a Java framework based on Selenium, Cucumber and Gherkin stack to create GUI testing projects that can be included in the continuous integration chain of single/multi applications web solution builds.
    * [Cubano](https://concordion.org/cubano/framework) - Cubano is a test automation framework written in Java that provides a structure for developing acceptance and regression tests so your team can hit the ground running and not have to waste time needlessly building and maintaining your own framework.
    * [Jalenium](https://lkkushan.gitbook.io/jalenium/) - Jalenium is a Java Selenium API which can be easily integrated to any maven Selenium Java project which uses Selenium JAR files.
    * [TestZeus](http://testzeus.com/) - Open source UI Test automation framework built specifically for Salesforce with Autolocators.
    
- extensions
    * [BrowserMob Proxy](https://github.com/lightbody/browsermob-proxy) - Is a simple utility that makes it easy to capture performance data from browsers, typically written using automation toolkits such as Selenium and Watir.
    * [Selenoid](https://github.com/aerokube/selenoid) - Selenium Hub successor running browsers within containers. Scalable, immutable, self hosted Selenium-Grid on any platform with single binary.
    * [Selenium-Grid-Extras](https://github.com/groupon/Selenium-Grid-Extras) - Simplify the management of the Selenium Grid Nodes and stabilize said nodes by cleaning up the test environment after the build has been completed
    * [Selenium Grid Extensions](https://github.com/sterodium/selenium-grid-extensions) - Extend Selenium grid with extra functionality. Execute Sikuli tests in combination with Selenium.
    * [Selenium Grid Router](https://github.com/seleniumkit/gridrouter) is a lightweight server that routes and proxies Selenium Wedriver requests to multiple Selenium hubs.
    * [Docker Selenium Grid](https://github.com/sskorol/docker-selenium-grid) - A project to provide native video recording support for Selenium Grid and was initially designed to be used with docker-selenium project.
    * [Video Recorder Java](https://github.com/SergeyPirogov/video-recorder-java) - This library allows easily record video of your UI tests by just putting couple annotations.
    * [Zalenium](https://github.com/zalando/zalenium) - Allows anyone to have a disposable and flexible Docker-based Selenium Grid infrastructure featuring video recording, live preview and online/offline dashboards.
    * [SikuliFactory](https://github.com/marcoslimaqa/sikuli-factory) - A based PageFactory model for SikuliX.
    * [Mailosaur](https://github.com/mailosaur/mailosaur-java) - Java client for email testing/automation via Mailosaur.
    * [TrueAutomation.IO](https://trueautomation.io/) - One of the main tasks of TA is to solve problem of working with unstable locators.

## Mobile test automation

* [Appium](http://appium.io/) - An open source test automation framework for use with native, hybrid and mobile web apps. It drives iOS and Android apps using the WebDriver protocol.
* [Calabash](http://calaba.sh/) - A cross-platform test automation framework for Android and iOS native and hybrid applications. Calabash’s easy-to-understand syntax enables even non-technical people to create and execute automated acceptance tests for apps on both of these mobile platforms.
* [Robotium](https://code.google.com/p/robotium/) - An Android test automation framework that fully supports native and hybrid applications. Robotium makes it easy to write powerful and robust automatic black-box UI tests for Android applications. With the support of Robotium, test case developers can write function, system and user acceptance test scenarios, spanning multiple Android activities.
* [UIautomator](http://developer.android.com/tools/help/uiautomator/index.html) - Provides an efficient way to test UIs. It creates automated functional test cases that can be executed against apps on real Android devices and emulators. It includes a viewer, which is a GUI tool to scan and analyze the UI components of an Android app.
* [Espresso](https://code.google.com/p/android-test-kit/wiki/Espresso) - A pretty new test automation framework that got open-sourced just last year, making it available for developers and testers to hammer out their UIs. Espresso has an API that is small, predictable, easy to learn and built on top of the Android instrumentation framework. You can quickly write concise and reliable Android UI tests with it.

## API test automation

* [hikaku](https://github.com/codecentric/hikaku) - A library that tests if the implementation of a REST-API meets its specification. 
* [Karate-DSL](https://github.com/intuit/karate) - Karate is a BDD javascript framework which enables you to script a sequence of calls to any kind of web-service and assert that the responses are as expected. It makes it really easy to build complex request payloads, traverse data within the responses, and chain data from responses into the next request. Karate's payload validation engine can perform a 'smart compare' of two JSON or XML documents without being affected by white-space or the order in which data-elements actually appear, and you can opt to ignore fields that you choose.
* [Retrofit](http://square.github.io/retrofit/) - A type-safe HTTP client for Android and Java.
* [REST-Assured](https://github.com/rest-assured/rest-assured) - A library for testing and validation of REST services in Java.


## Windows UI test automation

* [SikuliX](http://www.sikulix.com/) - SikuliX automates anything you see on the screen of your desktop computer running Windows, Mac or some Linux/Unix. It uses image recognition powered by OpenCV to identify and control GUI components. This is handy in cases when there is no easy access to a GUI's internals or the source code of the application or web page you want to act on.
* [Winium for Desktop](https://github.com/2gis/Winium.Desktop/) - Winium.Desktop is an open source test automation tool for automated testing of Windows application based on WinFroms and WPF platforms.
* [WinAppDriver](https://github.com/microsoft/WinAppDriver) - Windows Application Driver (WinAppDriver) is a service to support Selenium-like UI Test Automation on Windows Applications. This service supports testing Universal Windows Platform (UWP), Windows Forms (WinForms), Windows Presentation Foundation (WPF), and Classic Windows (Win32) apps on Windows 10 PCs.

## Unix \ Linux UI test automation

* [SikuliX](http://www.sikulix.com/) - SikuliX automates anything you see on the screen of your desktop computer running Windows, Mac or some Linux/Unix. It uses image recognition powered by OpenCV to identify and control GUI components. This is handy in cases when there is no easy access to a GUI's internals or the source code of the application or web page you want to act on.

## MacOS UI test automation

* [SikuliX](http://www.sikulix.com/) - SikuliX automates anything you see on the screen of your desktop computer running Windows, Mac or some Linux/Unix. It uses image recognition powered by OpenCV to identify and control GUI components. This is handy in cases when there is no easy access to a GUI's internals or the source code of the application or web page you want to act on.

## Server side test automation

* [Citrus](https://github.com/christophd/citrus) - Test framework written in Java that is able to create fully automated end-to-end use case tests for enterprise SOA applications. Citrus simulates surrounding interface partners supporting a huge set of different transports and protocols like HTTP, JMS, TCP/IP, FTP, SOAP, XML and JSON.

## Virtual environments

* [Vagrant](https://www.vagrantup.com/) - Easy to configure, reliable tool for building and maintaining portable virtual development environments.
* [Docker](https://www.docker.com) - Docker is the world’s leading software container platform. Developers use Docker to eliminate “works on my machine” problems when collaborating on code with co-workers. Operators use Docker to run and manage apps side-by-side in isolated containers to get better compute density. Enterprises use Docker to build agile software delivery pipelines to ship new features faster, more securely and with confidence for both Linux and Windows Server apps.

## Performance & stress & load

* [Apache JMeter](http://jmeter.apache.org/) - Functional testing and performance measurements.
* [The Grinder](http://grinder.sourceforge.net/) - Load testing framework that makes it easy to run a distributed test using many load injector machines.
* [Lightning](http://automatictester.github.io/lightning/) - Integrate JMeter non-functional tests with CI/CD server.
* [Tsung](http://tsung.erlang-projects.org/) - Erlang based multi-protocol distributed load testing tool.
* [Gatling](http://gatling.io/) - Gatling is an open-source load testing framework based on Scala, Akka and Netty. Is a highly capable load testing tool. It is designed for ease of use, maintainability and high performance. Based on an expressive DSL, the scenarios are self explanatory. They are easy to maintain and can be kept in a version control system. Gatling  architecture lets implement virtual users as messages instead of dedicated threads, making them very resource cheap. Thus, running thousands of concurrent virtual users is not an issue.
* [CRUX](https://github.com/ObjectivityLtd/crux) - (pron. kruhks) is build around Kubernetes (AKS) and JMeter. It makes it easy to incorporate performance tests into your Azure CI/CD pipeline. Each performance build can create and destroy infrastructure necessary for the run, which makes it cost effective. CRUX deploys a distributed JMeter cluster on Kubernetes (AKS) with the size you need, runs tests, destroys infrastructure. If you do not have an AKS, be at ease, you can also run JMeter tests with CRUX directly on build agent with docker.

## Security checking

* [BDD-Security](https://github.com/iriusrisk/bdd-security) - BDD-Security is a security testing framework that uses natural language in a Given, When, Then Gherkin syntax to describe security requirements as features. Those same requirements are also executable as standard unit/integration tests which means they can run as part of the build/test/deploy process.

## Build Tools

* [Apache Ant](http://ant.apache.org/) - Apache Ant is a Java library and command-line tool whose mission is to drive processes described in build files as targets and extension points dependent upon each other. The main known usage of Ant is the build of Java applications.
* [Apache Maven](http://maven.apache.org/) - Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.
* [Gradle](https://gradle.org/) - Gradle is an open source build automation system. Gradle can automate the building, testing, publishing, deployment and more of software packages or other types of projects such as generated static websites, generated documentation or indeed anything else.

## Continuous Integration

* [Jenkins](http://jenkins-ci.org/) - Jenkins is an award-winning application that monitors executions of repeated jobs, such as building a software project or jobs run by cron.
* [TeamCity](https://www.jetbrains.com/teamcity/) - Powerful and user-friendly Continuous Integration and Deployment server that works out of the box.
* [Drone](https://drone.io/) Drone is a self-service Continuous Integration platform for busy development teams.
* [Thundra Foresight](https://www.thundra.io/foresight) Thundra Foresight is a CI observability tool that provides visibility into your test suites.

## Reporting

* [ReportPortal](https://github.com/reportportal/reportportal) - powerful server-client reporting tool. Reduce the effort to work with results. Powered with Machine Learning, Providing historical data (statues) of executions in on click, logs, screenshost and any binary attachement. Trends, flaky test, most failed, longest test via custom widgets and dashboards, which give visibility to the team, leads, managers and falcon-eye view for VPs. Provide ability to categorize fails by custom defect types and utilize power of Machine Learning to detect fails, based on collected patterns. Give benefits of real-time integration: no need to wait execution ending.  Any language, any platform. Free, Open Sourced. [Java integrations](https://github.com/reportportal?utf8=✓&q=agent-java&type=&language=)
* [Allure](https://docs.qameta.io/allure/latest) - Open-source framework designed to create test execution reports clear to everyone in the team.
* [Gradle Allure Plugin](https://github.com/d10xa/gradle-allure-plugin) - 3rd-party Gradle Allure Plugin allows you to integrate Allure into spock, testing and junit tests.
* [ExtentReports](http://relevantcodes.com/extentreports-for-selenium/) - HTML reporting library for .NET and Java which is extremely easy to use and creates beautiful execution reports. It shows test and step summary, test steps and status in a toggle view for quick analysis.
* [ReportNG](http://reportng.uncommons.org/) - ReportNG is a simple HTML reporting plug-in for the TestNG unit-testing framework.
* [Zebrunner Reporting](https://github.com/zebrunner/reporting) -Zebrunner Reporting is a test automation management tool that accumulates and represents test results. It is designed to increase the transparency of automation, providing detailed reports with test logs, screenshots and video recordings of test sessions.
* [Difido-reports](http://top-q.github.io/difido-reports/) - This project aims to provide a generic implementation for HTML test reports.
* [cucumber-reporting](https://github.com/damianszczepanik/cucumber-reporting) - This is a Java report publisher primarily created to publish cucumber reports on the Jenkins build server. It publishes pretty html reports with charts showing the results of cucumber runs. It has been split out into a standalone package so it can be used for Jenkins and maven command line as well as any other packaging that might be useful. Generated report has no dependency so can be viewed offline.
* [Cluecumber](https://github.com/trivago/cluecumber) - This is reporting library for the Cucumber JSON format as it is produced by Cucumber and Karate. It provides clear and concise HTML reports and is highly customizable.

## Documentation generation

[Contribute to this section](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)

## Editors, IDE, consoles

* [IntelliJ IDEA](https://www.jetbrains.com/idea/) - A free and open-source IDE for Java, Groovy, Scala and Android development.
    * [IntelliJ IDEA Selenium plugin](http://perfect-test.com/index.php/ru/instruments-rus-menu/15-selenium-plugin-rus) - Plugin for IntelliJ Idea to simplify creation of web tests using selenium.
* [Eclipse](https://eclipse.org/ide/) - Eclipse is famous for our Java Integrated Development Environment (IDE), C/C++ IDE and PHP IDE.
    * [Genie plugin](https://sourceforge.net/adobe/genie/wiki2/FAQ/) - Functional Test Automation tool for pure AS 3.0 SWF and Flash Games.  
* [NetBeans](https://netbeans.apache.org/front/main/index.html) - NetBeans IDE is the official IDE for Java 8. With its editors, code analyzers, and converters, you can quickly and smoothly upgrade your applications to use new Java 8 language constructs, such as lambdas, functional operations, and method references.
* [VSCode](https://code.visualstudio.com/) Code editing. Redefined.

## ORM frameworks and libraries

* [Hibernate](http://hibernate.org/orm/) - Hibernate ORM enables developers to more easily write applications whose data outlives the application process. As an Object/Relational Mapping (ORM) framework, Hibernate is concerned with data persistence as it applies to relational databases (via JDBC).
* [Morphia](https://github.com/mongodb/morphia) - Morphia is a lightweight type-safe library for mapping Java objects to/from MongoDB. Morphia provides a typesafe, and fluent Query API support with (runtime) validation. Morphia uses annotations so there are no XML files to manage or update. Morphia should feel very comfortable for any developer with JPA experience.
* [MyBatis](http://www.mybatis.org/mybatis-3) - MyBatis is a first class persistence framework with support for custom SQL, stored procedures and advanced mappings. MyBatis eliminates almost all of the JDBC code and manual setting of parameters and retrieval of results. MyBatis can use simple XML or Annotations for configuration and map primitives, Map interfaces and Java POJOs (Plain Old Java Objects) to database records.

## Useful libs

* [StreamEx](https://github.com/amaembo/streamex) - Common Java 8 Streams enhancement library.
* [Vavr](https://github.com/vavr-io/vavr) - Vavr is an object-functional language extension to Java 8, which aims to reduce the lines of code and increase code quality. It provides persistent collections, functional abstractions for error handling, concurrent programming, pattern matching and much more.
* [Lombok](https://projectlombok.org) - Project Lombok makes Java a spicier language by adding 'handlers' that know how to build and compile simple, boilerplate-free, not-quite-java code.
* [AspectJ](https://eclipse.org/aspectj) - Seamless aspect-oriented extension to the Java. AspectJ enables clean modularization of crosscutting concerns, such as error checking and handling, synchronization, context-sensitive behavior, performance optimizations, monitoring and logging, debugging support, and multi-object protocols.
* [aShot](https://github.com/yandex-qatools/ashot) - WebDriver Screenshot utility. Take screenshots, crop, prettify, compare.
* [WireMock](http://wiremock.org/) is a flexible library for stubbing and mocking web services. Unlike general purpose mocking tools it works by creating an actual HTTP server that your code under test can connect to as it would a real web service.
* [MockServer](http://www.mock-server.com/) can be used for mocking any system you integrate with via HTTP or HTTPS (i.e. services, web sites, etc).
* [Mockito](http://site.mockito.org/) is a mocking framework that lets you write beautiful tests with a clean & simple API.
* [PowerMock](https://github.com/powermock/powermock) is a Java framework that allows you to unit test code normally regarded as untestable.
* [XMLUnit](http://www.xmlunit.org/) - testing and comparing XML output for Java and .NET
* [Awaitility](https://github.com/awaitility/awaitility) - Awaitility is a DSL that allows you to express expectations of an asynchronous system in a concise and easy to read manner.
* [Beanmother](https://github.com/keepcosmos/beanmother) - A library for setting up Java Bean as test data.
* [PIT](http://pitest.org) - Pitest, a tool for mutation testing
* [GreenMail](https://greenmail-mail-test.github.io/greenmail/) - GreenMail is an open source, intuitive and easy-to-use test suite of email servers for testing purposes. Typical use cases include mail integration testing or a lightweight sandboxed mail server for development.
* [image-comparison](https://romankh3.github.io/image-comparison/) - Java Library that compares 2 images with the same sizes and shows the differences visually by drawing rectangles. Some parts of the image can be excluded from the comparison. Can be used for automation qa tests.
* [AssertJ](https://joel-costigliola.github.io/assertj/) - Powerful fluent assertion framework. Compatible with any xUnit framework.
* [Truth](https://truth.dev/) - Fluent assertion framework for Java and Android from Google.
* [JSONassert](https://github.com/skyscreamer/JSONassert) - JSON assertion library.
* [selenium-to-restassured](https://github.com/mwinteringham/selenium-to-restassured) - Adapter to easily share Selenium WebDriver cookies with Rest Assured back and forth with this Java api.
* [TestRail-JUnit](https://github.com/RSheremeta/TestRail-JUnit) - This Library helps you to integrate your JUnit-based tests with TestRail in an easily manner. 
* [TestRail-TestNG](https://github.com/RSheremeta/TestRail-TestNG) - This Library helps you to integrate your TestNG-based tests with TestRail in an easily manner.
* [Allure-Environment-Creator](https://github.com/RSheremeta/Allure-Environment-Creator) - This tiny Library helps you to serve and store environment data for Allure easily.
* [Owner](https://github.com/lviggiano/owner) - The OWNER API is a Java library with the goal of minimizing the code required to handle application configuration via Java properties files.
* [DeepfakeHTTP](https://github.com/xnbox/DeepfakeHTTP) - DeepfakeHTTP is a web server that uses HTTP dumps as a source for responses. This tool allows you to test clients against REST, GraphQL, and other APIs.
* [Cucable](https://github.com/trivago/cucable-plugin) - Cucable is a Maven plugin that simplifies running Cucumber scenarios in parallel by slicing them into the smallest runnable feature files and runner classes.

## Test Data
* [Faker](https://github.com/datafaker-net/datafaker) - Java implementation of Faker, a library for generating fake data such as names, addresses, and phone numbers.
* [Instancio](https://github.com/instancio/instancio) - Creates fully-populated objects for your unit tests. Includes an extension for JUnit 5.

## DataBase test automation
* [DBTestCompare](https://github.com/ObjectivityLtd/DBTestCompare) - Application to compare results of two SQL queries. Supports all databases with JDBC drivers provided (tested with Microsoft SQL Server, Teradata, Snowflake, PostgreSQL and MySQL\MariaDB). [DBTestCompareGenerator](https://github.com/ObjectivityLtd/DBTestCompareGenerator) - Tool for generating database tests that can be run with DBTestCompare.

# Resources
* [Serenity BDD (Thucydides) libraries](https://github.com/thucydides-webtests/thucydides)
* [Automation tests structure](http://habrahabr.ru/post/168451/)

## Websites

* [automated-testing.info](http://automated-testing.info) - Test automation community
* [atinfo.github.io/at.info-knowledge-base](http://atinfo.github.io/at.info-knowledge-base/)  - Knowledge base for test automation examples on different tools and technologies
* [selenium-simplified](http://seleniumsimplified.com/) - AUTOMATED BROWSER TESTING WITH SELENIUM 2 WEBDRIVER – MADE SIMPLE

# Other Awesome Test Automation Lists

* [python test automation](https://github.com/atinfo/awesome-test-automation/blob/master/python-test-automation.md) 
* [java test automation](https://github.com/atinfo/awesome-test-automation/blob/master/java-test-automation.md) 
* [ruby test automation](https://github.com/atinfo/awesome-test-automation/blob/master/ruby-test-automation.md) 
* [c# test automation](https://github.com/atinfo/awesome-test-automation/blob/master/c%23-test-automation.md) 
* [php test automation](https://github.com/atinfo/awesome-test-automation/blob/master/php-test-automation.md) 
* [javascript test automation](https://github.com/atinfo/awesome-test-automation/blob/master/javascript-test-automation.md) 
* [kotlin test automation](https://github.com/atinfo/awesome-test-automation/blob/master/kotlin-test-automation.md) 
* [test automation and software testing as services](https://github.com/atinfo/awesome-test-automation/blob/master/automation-and-testing-as-service.md) 
* [mobile, tablet and tv test automation](https://github.com/atinfo/awesome-test-automation/blob/master/mobile-test-automation.md)
* [general purpose test automation tools](https://github.com/atinfo/awesome-test-automation/blob/master/general-purpose-test-automation-tools.md)

Also we are supporting and looking for contribution for project:

* [practical test automation by examples](https://github.com/atinfo/at.info-knowledge-base)

# [Contributing](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)
Your contributions are always welcome!