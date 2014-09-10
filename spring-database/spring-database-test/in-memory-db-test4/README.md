Java Example Projects
========

This repository contains example projects for various java technologies.

There are separate folders for each technology.

Projects are setup for Maven.


Spring
======

String and tests with in memory database
------

* `in-memory-db-tests`, this project just puts together the code from article:

>>   [Unit Testing with an In-Memory Database for a Spring/Hibernate Project](http://whileonefork.blogspot.fr/2012/11/unit-testing-with-in-memory-database.html)

* `InMemoryDbTests2` updates the previous project with JPA 2.1, Spring 4, Hibernate 4 and commons-dbcp2

* `InMemoryDbTests3` replaces XML Spring configuration with a (almost) pure java one.

* `InMemoryDbTests4` updates logging and uses DataSourceInitializer to populate the database with the same data before each test.