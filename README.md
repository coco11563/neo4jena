Neo4Jena
========
Overview
--------

For the integration of Jena and neo4j we have implemented Jena graph interfaces using neo4j native API.
Neo4Jena is a property graph model interface. It provides the mapping of RDF to property graph (Neo4J) using Jena API.  The main work focuses on how RDF triple is converted to Neo4j graph and vice versa. After the successful loading of RDF in graph we retrieve the data using SPARQL.  We made the following contributions:
* Firstly RDF triples (subject, predicate and object) are converted to Neo4j node and relationship. 
* After the conversion, it store triples in Neo4j graph.
* After the successful loading of RDF triples in graph Neo4Jena retrieve the data using SPARQL. For this neo4j nodes and relationship is converted to RDF triples (subject, predicate and object).
* Neo4Jena has full support of SPARQL 1.1.


The mappings of RDF to Neo4j can be found at this [location](https://github.com/semr/neo4jena/wiki/Mappings). The [developer guide](https://github.com/semr/neo4jena/wiki/Developer's-Guide) is also available.
