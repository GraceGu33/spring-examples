Article d'origine :
Unit Testing with an In-Memory Database for a Spring/Hibernate Project 
http://whileonefork.blogspot.fr/2012/11/unit-testing-with-in-memory-database.html
Ni dépôt ni fichier à télécharger

Mise au goût du jour : utilisation de JPA en version JPA 2.1., avec annotations
Màj vers Spring 4 (°), Hibernate 4 et commons-dbcp2

Voir InMemoryDbTestBase.java quant à la façon de récupérer une configuration
pour SchemaExport avec hibernate 4.

Note (°). In fact Spring 4.1.0.RC2 is required, see:
	Isolation support for JPA with Hibernate EntityManager 4
	https://jira.spring.io/browse/SPR-11942

Pour la bdd, conserver InMemoryDbBase.setup/teardown