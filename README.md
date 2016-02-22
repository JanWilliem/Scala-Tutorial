# Scala Tutorial

Information, references, sample code, and anything else related to learning the Scala language.

## What Is Scala?

*From http://www.scala-lang.org/what-is-scala.html*

> Scala is an acronym for “Scalable Language”. This means that Scala grows with you. You can play with it by typing one-line expressions and observing the results. But you can also rely on it for large mission critical systems, as many companies, including Twitter, LinkedIn, or Intel do. To some, Scala feels like a scripting language. Its syntax is concise and low ceremony; its types get out of the way because the compiler can infer them. There’s a REPL and IDE worksheets for quick feedback. Developers like it so much that Scala won the ScriptBowl contest at the 2012 JavaOne conference. At the same time, Scala is the preferred workhorse language for many mission critical server systems. The generated code is on a par with Java’s and its precise typing means that many problems are caught at compile-time rather than after deployment. At the root, the language’s scalability is the result of a careful integration of object-oriented and functional language concepts.

*From http://joelabrahamsson.com/learning-scala/*

> Scala is a statically typed language that was conceived in 2001 by Martin Odersky, who has also written the Java reference compiler and co-authored Java generics. It is both a functional language, meaning that functions are values, and also an object oriented language where every value is an object. Scala compiles to byte code for the Java Virtual Machine (JVM) making it platform independent. That also means that we from a Scala program can use existing Java libraries and vice versa.

## IDE Setup for Scala & ScalaTest

Eclipse and IntelliJ have plugins for scala that are under active development with a large community of users.

### Eclipse

The Scala IDE plugin site has [Eclipse setup instructions](http://scala-ide.org/docs/current-user-doc/gettingstarted/index.html). There is a separate plugin to add [ScalaTest support in Eclipse](https://github.com/scalatest/scalatest-eclipse-plugin/blob/master/README.rst). If you are using m2eclipse, [install the m2eclipse-scala plugin](http://scala-ide.org/docs/current-user-doc/gettingstarted/index.html#Import_a_Maven_project) to remove the scala POM errors.

### IntelliJ

JetBrains maintains the Scala Plugin (which has ScalaTest support built-in) and has [IntelliJ setup instructions](http://confluence.jetbrains.com/display/SCA/Getting+Started+with+IntelliJ+IDEA+Scala+Plugin).

### ExpWeb Specific Instructions

There are special notes for ExpWeb and Scala on the [CKO ScalaTest Tutorial](https://confluence/display/POS/CKO+Scalatest+tutorial) confluence page.

## How Can I Get Help?

- **[EWE Scala](https://expedia.hipchat.com/rooms/show/224035/ewe_scala)** HipChat Room
- **scala@expedia.com** DL

## Style Guidelines

Twitter has an [Effective Scala](http://twitter.github.io/effectivescala/) style guide with lots of good tips. We will use this as a starting point, and add extensions to this as we learn. 

**As a general rule, do not use the complex features of Scala unless they improve readability and maintainability for everyone (and not just Scala experts).** This rule applies to the code we write and also to third party APIs that we consume.

## Online Courses and Resources

- **[Twitter Scala School](http://twitter.github.io/scala_school/)** - This is how Twitter ramps up new and experiences developers.
- **[Coursera Function Programming In Scala](https://www.coursera.org/course/progfun)** - This does not represent day-to-day coding in Scala, but many in EWE have taken this class and it shows some of the real power and intent of Scala.
- **[Scala Cheatsheet](http://docs.scala-lang.org/cheatsheets/)** - Quick reference while you're getting the hang of Scala functionality and syntax.
- **[Scala For Java Developers](http://docs.scala-lang.org/tutorials/scala-for-java-programmers.html)** - Quick tutorial on the basics for Java developers.
- **[Simply Scala](http://www.simplyscala.com/)** - Try out some Scala code samples
- **[Scala Koans](http://scalakoans.webfactional.com/)** - Test your Scala knowledge, see how many tests you can get to pass!
- **[Scala For Beginners](http://workday.github.io/scala/2014/01/09/scala-for-beginners/)** - WorkDay has a bunch of good links for new Scala devs here.
- **[Scala Exercices](http://scala-exercises.47deg.com)** - Perfect to learn with interactive exercises divided by topics, starting from basics to intermediate material. 

## Books

- **[TypeSafe E-Book Resources](http://typesafe.com/resources/e-books)** - Covering Play, Reactive, Java 8, and Scala
- **[Programming in Scala, 2nd Edition](http://www.chegg.com/textbooks/programming-in-scala-2nd-edition-9780981531649-0981531644)** - Written by Martin Odersky, the creator of Scala.
- **[Scala By Example (FREE)](http://www.scala-lang.org/docu/files/ScalaByExample.pdf)** - Written by Martin Odersky
- **[Scala for the Impatient](http://www.chegg.com/textbooks/scala-for-the-impatient-1st-edition-9780321774095-0321774094)** - Let us know if this book is as good as it is supposed to be!

## Who Is 100% Scala?

*Please add your project to this list if your application is 100% Scala.*

- [LXHub](https://github.com/LocalExpert/lxhub-scala-api) - *You need permissions to view this repo*. LX Hub API service.
- [EWE TDA](https://ewegithub.sb.karmalab.net/EWE/expedia-tools-ewetda) - Thread dump analysis tool from Platform team.
- [Ads DFP Migration](https://ewegithub.sb.karmalab.net/EWE/ads-dfp-migration) - Migrates data from DoubleClick for Enterprise to DoubleClick for Publishers.
- [Platform Monitoring Relay](https://ewegithub.sb.karmalab.net/EWE/platform-monitoring-relay) - Updated OSS Graphite relay
- [Collector Web](https://ewegithub.sb.karmalab.net/EWE/collector-web) - Entry point to doppler platform
- [TFJPAD](https://ewegithub.sb.karmalab.net/EWE/travelfusionprovideradapter-service) - TravelFusion provider adapter service

## What Scala APIs Are In Use?

*Please add links and comments to any APIs that you have used or did not use.*

The scala-lang website has a [wiki with a list of Scala APIs](https://wiki.scala-lang.org/display/SW/Tools+and+Libraries) that serves as a good starting point.

| API | Comment |
| --- |:------- |
| [ScalaTest](http://www.scalatest.org/) | Most EWE projects use this API for test automation. It has nice support for many types of test structures and has Selenium integration for UI testing. |
| [Scoverage](http://scoverage.org) | Code coverage tool, used in TFJPAD |
| [Scalastyle](http://www.scalastyle.org) | Code style checks, used in TFJPAD |

