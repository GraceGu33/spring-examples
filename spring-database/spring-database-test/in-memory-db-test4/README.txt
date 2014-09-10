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

Ajout de la journalisation

Ajout de la réinitialisation de la Bdd avant chaque test


Pour la publication sur GitHub, s'inspirer de la structure de dossier de 
	https://github.com/pkainulainen
		
		
Utilisation des @Profile 
Cf. 5.13.1 Bean definition profiles
    http://docs.spring.io/spring/docs/current/spring-framework-reference/html/beans.html#beans-definition-profiles		