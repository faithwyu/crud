﻿# CRUD: A Survey of Database Technology

## Abstract
The relational database has been the dominant tool for data storage over the past thirty years. But with the growth of the web has come new requirements for faster searching and storing of large amounts of data and new tools have risen to meet those demands. This course will review the basics of relational databases as a foundation and as a basis for comparison to other tools. From there, we will look at alternative NoSQL databases (columnar, keystore, document, and graph), as well as search indexes, triplestores, and NewSQL databases. In-depth coverage of any topic should not be expected. The objective of the course is to give students an understanding of the wide variety of database solutions and the tradeoffs of using one over another.

## Prerequisites

### Required
- A laptop with Docker and Git installed:
    - Git: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
    - Docker: https://www.docker.com/community-edition#/download
- Curiosity and fearlessness about trying new things.

### Helpful
- Basic understanding of relational databases and SQL. 
- Prior programming experience in Python.

## Instructor
Joshua Gomez, Sr. Software Engineer, Getty Research Institute

joshuagomez@ucla.edu

## Grading
- 10% Quizzes
- 20% In-class Exercises
- 70% Homework

## Texts

***All texts are optional!***

- Elmasri & Navathe, Fundamentals of Database Systems, 6th ed., 2010. 
    - *Recommended if you have not taken a prior course in databases.*
    - ***Use the older (and much cheaper!) 6th edition***
- Harrison, Next Generation Databases, 2015.
    - ***Electronic version available via UCLA Library:*** [http://ucla.worldcat.org/oclc/933784067](http://ucla.worldcat.org/oclc/933784067_)

## Schedule

### Week 1
|  |  |
|--:|--|
|Topics:|Course Introduction<br/>Relational Database Concepts<br/>Entity-Relationship Modeling<br/>Basic SQL |
| Tools:|[SQLite](https://sqlite.org/docs.html) |
| Readings:|Elmasri: chapters 3-4, 7, 9 |

### Week 2
|  |  |
|--:|--|
|Topics:|RDBMS Architecture<br/>Normalization<br/>Intermediate SQL|
| Tools:|[SQLite](https://sqlite.org/docs.html)|
| Readings:|Elmasri: chapters 2, 5, 15|

### Week 3
|  |  |
|--:|--|
|Topics:|Transactions & ACID Properties<br/>Triggers<br/>SQL Functions|
| Tools:|[MySQL](https://dev.mysql.com/doc/refman/5.7/en/)|
|  Readings:|Elmasri: chapters 21, 26.1|

### Week 4
|  |  |
|--:|--|
|Topics:|Acess Structures<br/>Optimization<br/>Security|
| Tools:|[PostgreSQL](https://www.postgresql.org/docs/10/static/index.html) |
|  Readings:|Elmasri: chapter 20, 24|

### Week 5
| | |
|--:|--|
|Topics:|Replication<br/>Partitions<br/>Advanced SQL<br/>GIS & Time series data (if time permits)|
| Tools:|[PostgreSQL](https://www.postgresql.org/docs/10/static/index.html) |
|  Readings:|Elmasri: chapter 25, 26|

### Week 6
|  |  |
|--:|--|
|Topics:|Intro to Information Retrieval<br/>Web Search<br/>Faceted Search|
| Tools:|[ElasticSearch](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html)  |
|  Readings:|Elmasri: chapter 27|

### Week 7
|  |  |
|--:|--|
|Topics:|Intro to NoSQL Databases<br/>CAP Theorem<br/>Columnar Databases|
| Tools:|[HBase](https://lucene.apache.org/solr/resources.html)<br/>[Cassandra](https://cassandra.apache.org/)|
|  Readings:|[Google’s Bigtable Paper](https://research.google.com/archive/bigtable.html) (Chang et al., 2006)<br/>[Facebook’s Cassandra Paper](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf) (Lakshman et al., 2009)|

### Week 8
|  |  |
|--:|--|
|Topics:|Key Stores|
| Tools:|[Riak](http://basho.com/products/#riak)<br/>[Redis](http://redis.io/)|
|  Readings:|[Amazon’s Dynamo Paper](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf) (DiCandia et al., 2007)|

### Week 9
|  |  |
|--:|--|
|Topics:|Document Stores & MapReduce|
| Tools:|[MongoDB](https://www.mongodb.com/)<br/>[PostgreSQL](https://www.postgresql.org/docs/10/static/index.html) revisited|
|  Readings:|*TBD*|

### Week 10
|  |  |
|--:|--|
|Topics:|Graph Databases|
| Tools:|[Neo4j](https://neo4j.com/)<br/>[ArrangoDB](https://arangodb.com/)|
|  Readings:|*TBD*|

### Week 11 - *(Bonus material if time permits)*
|  |  |
|--:|--|
|Topics:|Linked Data<br/>Triplestores<br/>SPARQL|
| Tools:|[GraphDB](http://graphdb.ontotext.com/documentation/free/)|
|  Readings:|*TBD*|

### Week 12 - *(Bonus material if time permits)*
|  |  |
|--:|--|
|Topics:|NewSQL Databases|
| Tools:|[CockroachDB](https://www.cockroachlabs.com/install-getstarted/)|
|  Readings:|*TBD*|
