# Programming Is Awesome
    
This is a collection of many frameworks and tools for software development.

Any **recommendations** and **suggestions** are welcomed.

## Table of Contents

- [Architecture](#architecture)
- [Cloud Providers](#cloud-providers)
- [Big Data](#big-data)
    - [Big Data Distributor](#big-data-distributor)
    - [Big Data Ingestion Layer](#big-data-ingestion-layer)
    - [Big Data Speed Layer](#big-data-speed-layer)
    - [Big Data Batch Layer](#big-data-batch-layer)
    - [Resource Manager](#resource-manager)
    - [Distributed SQL Query Engine](#distributed-sql-query-engine)
    - [Machine Learning](#machine-learning)
    - [Machine Learning Tools](#machine-learning-tools)
    - [Notebook](#notebook)
- [Database](#database)
    - [Column Family](#column-family)
    - [Document Oriented](#document-oriented)
    - [Search DB](#Search-db)
    - [Graph DB](#graph-db)
    - [NewSQL](#newsql)
    - [In-memory DB](#in-memory-db)
    - [Event Store](#event-store)
    - [Embedded Database](#embedded-database)
    - [Time Series](#time-series)    
- [Data Warehouse](#data-warehouse)
- [Storage](#storage)
- [Distributed File System](#distributed-file-system)
- [BI Tools](#bi-tools)
- [Parallel Programming](#parallel-programming)   
- [Frameworks & Tools](#frameworks--tools)
    - [Reactive Framework](#reactive-framework)
    - [Micoservices Framework](#micoservices-framework)    
    - [Monitoring](#monitoring)
    - [Load Balancer](#load-balancer)
    - [API Gateway](#api-gateway)
    - [Testing Tools](#testing-tools)  
    - [Code Quality Analyzer](#code-quality-analyzer)  
    - [Code Security Analyzer](#code-security-analyzer)
    - [SQL Database Version Manager](#sql-database-version-manager)
    - [SMTP Server](#smtp-server)
    - [Profiling Tools](#profiling-tools)
- [DevOps](#devops)
- [Security](#security)
- [Mobile Frameworks](#mobile-frameworks)
- [Game Engines](#game-engines)
- [AI Tools](#ai-tools)
- [IoT](#iot)
    - [IoT OS](#iot-os)
- [UML Tools](#uml-tools)     
- [Summit Events](#summit-events)
- [Algorithms](#algorithms)

***********

## Architecture
- [Microservices](https://en.wikipedia.org/wiki/Microservices) - Microservices is a specialisation of and implementation approach for distributed architectures used to build flexible, independently deployable software systems.
- [Reactive Programming](https://en.wikipedia.org/wiki/Reactive_programming) - Reactive programming is about non-blocking applications that are asynchronous and event-driven and require a small number of threads to scale.
- [Lambda Architecture](http://lambda-architecture.net/) - Lambda architecture is a data-processing architecture designed to handle massive quantities of data by taking advantage of both batch- and stream-processing.
- [CQRS](http://martinfowler.com/bliki/CQRS.html) - Command and Query Responsibility Segregation (CQRS) is a pattern that segregates the operations that read data (Queries) from the operations that update data (Commands) by using separate interfaces.
- [Event Sourcing](http://microservices.io/patterns/data/event-sourcing.html) - Event Sourcing persists each business entity as a sequence of events.
- [Materialized View](https://en.wikipedia.org/wiki/Materialized_view) - A materialized view is a database object that contains the results of a query.

## Cloud Providers
- [Amazon Web Services (AWS)](https://aws.amazon.com/) - Amazon Web Services offers reliable, scalable, and inexpensive cloud computing services. Free to join, pay only for what you use.
- [Microsoft Azure](https://azure.microsoft.com/) - Microsoft Azure is an open, flexible, enterprise-grade cloud computing platform.
- [Google Cloud Platform](https://cloud.google.com/) - Google Cloud Platform lets you build and host applications and websites, store data, and analyze data on Google's scalable infrastructure.
- [IBM Bluemix](https://www.ibm.com/cloud-computing/bluemix/) - Bluemix is an open standards, cloud platform for building, running, and managing apps and services.
- [OpenStack](https://www.openstack.org/) - OpenStack software controls large pools of compute, storage, and networking resources throughout a datacenter.
- [Apache CloudStack](https://cloudstack.apache.org/) - Apache CloudStack is open source software designed to deploy and manage large networks of virtual machines.
- [Cloud Foundry](https://www.cloudfoundry.org/) - Cloud Foundry is an open source cloud computing platform as a service (PaaS) originally developed by VMware and now overseen by the Cloud Foundry.
- [DigitalOcean](https://www.digitalocean.com/) - DigitalOcean is a simple and robust cloud computing platform, designed for developers. 
- [Heroku](https://www.heroku.com/) - Heroku is a platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.
- [SAP HANA Cloud Platform](https://hcp.sap.com/index.html) - SAP HANA Cloud Platform is an open platform-as-a-service that provides unique in-memory database and application services.
- [Oracle Cloud](https://cloud.oracle.com/) - Oracle Cloud Platform as a Service (PaaS) helps enterprise IT and independent software vendor (ISV) developers rapidly build and deploy rich applications.

## Big Data

### Big Data Distributor
- [Amazon EMR](https://aws.amazon.com/emr/) - Amazon EMR simplifies big data processing, providing a managed Hadoop framework. 
- [Cloudera CDH](http://www.cloudera.com/) - CDH is Cloudera's software distribution containing Apache Hadoop and related projects. All components are 100% open source.
- [Hortonworks HDP](http://hortonworks.com/) - Hortonworks' product named Hortonworks Data Platform (HDP) includes Apache Hadoop and is used for storing, processing, and analyzing large volumes of data.
- [IBM BigInsights](http://www.ibm.com/analytics/us/en/technology/biginsights/) - IBM provides a complete solution of Hadoop, including Spark, to scale analytics quickly and easily. Available on-premises, on-cloud, and integrated with other systems in use today.
- [MapR](https://www.mapr.com/) - The MapR Converged Data Platform is the industry's only platform to integrate the enormous power of Hadoop and Spark with global event streaming, real-time.
- [Pivotal Big Data Suite](https://pivotal.io/big-data/pivotal-big-data-suite) - Pivotal Big Data Suite provides the flexibility to choose and adopt proven, open source, scale-out databases, including: Pivotal Greenplum, Pivotal HDB.
- [Databricks](https://databricks.com/) - Founded by the creators of Apache Spark, Databricks makes big data analytics simple through an integrated workspace hosted as a service in the cloud.
- [Concurrent](https://www.concurrent.com/) - One of the distributor in Hadoop world. 

### Big Data Ingestion Layer
- [Apache Kafka](https://kafka.apache.org/) - Kafka™ is used for building real-time data pipelines and streaming apps. 
- [Apache Flume](https://flume.apache.org/) - Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data.
- [RabbitMQ](https://www.rabbitmq.com/) - RabbitMQ is open source message broker software that implements the Advanced Message Queuing Protocol (AMQP).
- [Mosquitto](https://mosquitto.org/) - Mosquitto is an open source message broker that implements the MQTT (MQ Telemetry Transport) protocol v3.1.
- [Logstash](https://www.elastic.co/products/logstash) - Logstash is an open source, server-side data processing pipeline that ingests data from a multitude of sources simultaneously.
- [Spring XD](http://projects.spring.io/spring-xd/) - Spring XD is a unified, distributed, and extensible service for data ingestion, real time analytics, batch processing, and data export.

### Big Data Speed Layer
- [Confluent Platform](http://www.confluent.io/) - The free, open-source streaming platform based on Apache Kafka. Confluent Platform is the best way to get started with real-time data streams.
- [Apache Storm](http://storm.apache.org/) - Apache Storm is a free and open source distributed realtime computation system.
- [Apache Spark Streaming](http://spark.apache.org/streaming/) - Spark Streaming brings Apache Spark's language-integrated API to stream processing, letting you write streaming jobs the same way you write batch jobs.
- [Apache Flume Interceptor](https://flume.apache.org/) - Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data.
- [Apache Samza](http://samza.apache.org/) - Apache Samza is a distributed stream processing framework. It uses Apache Kafka for messaging, and Apache Hadoop YARN to provide fault tolerance.
- [Apache Gearpump](https://gearpump.apache.org/) - Apache Gearpump is a real-time big data streaming engine.
- [Spring XD](http://projects.spring.io/spring-xd/) - Spring XD is a unified, distributed, and extensible service for data ingestion, real time analytics, batch processing, and data export.

### Big Data Batch Layer
- [Apache Spark](http://spark.apache.org/) - Apache Spark™ is a fast and general engine for large-scale data processing.
- [Apache MapReduce](http://hadoop.apache.org/) - The Apache Hadoop MapReduce software library is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models.
- [Spring XD](http://projects.spring.io/spring-xd/) - Spring XD is a unified, distributed, and extensible service for data ingestion, real time analytics, batch processing, and data export.
- [Apache Flink](https://flink.apache.org/) - Apache Flink® is an open source platform for distributed stream and batch data.

### Resource Manager
- [Apache Mesos](http://mesos.apache.org/) - Apache Mesos abstracts CPU, memory, storage, and other compute resources away from machines (physical or virtual), enabling fault-tolerant and elastic distributed systems to easily be built and run effectively.
- [Mesosphere](https://mesosphere.com/) - Mesosphere Enterprise DC/OS is an enterprise grade datacenter-scale operating system, providing a single platform for running containers, big data.
- [Apache Yarn](http://hadoop.apache.org/) - The Apache Hadoop Yarn software library is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models.

### Distributed SQL Query Engine
- [Apache Impala](http://impala.apache.org/) - Apache Impala is the open source, native analytic database for Apache Hadoop. Impala is shipped by Cloudera, MapR, Oracle, and Amazon.
- [Apache Hive](https://hive.apache.org/) - Apache Hive is a data warehouse infrastructure built on top of Hadoop for providing data summarization, query, and analysis.
- [Spark SQL](http://spark.apache.org/sql/) - Spark SQL is a Spark module for structured data processing.
- [Apache Drill](https://drill.apache.org/) - Drill supports a variety of NoSQL databases and file systems, including HBase, MongoDB, MapR-DB, HDFS, MapR-FS, Amazon S3, Azure Blob Storage.
- [Presto](https://prestodb.io/) - Presto is an open source distributed SQL query engine for running interactive analytic queries against data sources of all sizes ranging.
- [Hive on Apache Tez](https://tez.apache.org/) - The Apache Tez™ project is aimed at building an application framework which allows for a complex directed-acyclic-graph of tasks for processing data.
- [Apache Phoenix](http://phoenix.apache.org/) - Apache Phoenix takes your SQL query, compiles it into a series of HBase scans.
- [Apache HAWQ](http://hawq.incubator.apache.org/) - Apache HAWQ (incubating) combines exceptional MPP-based analytics performance, robust ANSI SQL compliance, Hadoop ecosystem.
- [IBM Big SQL](http://www.ibm.com/analytics/us/en/technology/big-sql/) - IBM Big SQL is a data warehouse system for Hadoop that you use to summarize, query, and analyze data.
- [Apache Kylin](http://kylin.apache.org/) - Apache Kylin™ is an open source Distributed Analytics Engine.

### Machine Learning
- [Apache Mahout](https://mahout.apache.org/) - The Apache Mahout™ project's goal is to build an environment for quickly creating scalable performant machine learning applications.
- [Spark MLlib](http://spark.apache.org/mllib/) - MLlib is Apache Spark's scalable machine learning library.
- [H2O](http://www.h2o.ai/) - H2O is open-source software for big-data analysis.
- [Apache MADlib](https://madlib.incubator.apache.org/) - Apache MADlib (incubating): Big Data Machine Learning in SQL.
- [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Waikato Environment for Knowledge Analysis (Weka) is a popular suite of machine learning software written in Java, developed at the University of Waikato.
- [Scikit Learn](http://scikit-learn.org/stable/) - An open source Python library that implements a range of machine learning, preprocessing, cross-validation and visualization algorithms.
- [Apache SystemML](https://systemml.apache.org/) - Apache SystemML provides an optimal workplace for Machine Learning using big data.

### Machine Learning Tools
- [PyData](http://pydata.org/) - PyData is a gathering of users and developers of data analysis tools in Python.

### Notebook
- [Jupyter](http://jupyter.org/) - Open source, interactive data science and scientific computing across over 40 programming languages.
- [Zeppelin](https://zeppelin.apache.org/) - Apache Zeppelin interpreter concept allows any language/data-processing-backend to be plugged into Zeppelin.
- [RStudio](https://www.rstudio.com/) - A powerful and productive user interface for R.

## Database

### Column Family
- [DataStax Enterprise](http://www.datastax.com/) - DataStax powers the big data applications that transform business and profoundly improve customer experiences through Apache Cassandra™.
- [Amazon DynamoDB](https://aws.amazon.com/documentation/dynamodb/) - Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability.
- [Cassandra](http://cassandra.apache.org/) - The Apache Cassandra database is the right choice when you need scalability and high availability without compromising performance.
- [Apache HBase](http://hbase.apache.org/) - Apache HBase™ is the Hadoop database, a distributed, scalable, big data store. Use Apache HBase™ when you need random, realtime read/write access.
- [Apache Accumulo](https://accumulo.apache.org/) - Apache Accumulo™ is a sorted, distributed key/value store that provides robust, scalable data storage and retrieval.
- [Riak KV](http://basho.com/products/riak-kv/) - Riak® KV is a distributed NoSQL key-value database with advanced local and multi-cluster replication that guarantees reads and writes even in the event of hardware failures or network partitions.

### Document Oriented
- [MongoDB](https://www.mongodb.com/) - MongoDB for GIANT Ideas - Build innovative modern applications that create a competitive advantage.
- [CouchDB](http://couchdb.apache.org/) - Apache CouchDB is open source database software that focuses on ease of use and having an architecture that "completely embraces the Web".
- [Couchbase](http://www.couchbase.com/) - NoSQL database is developed by Couchbase.
- [DocumentDB](https://azure.microsoft.com/en-us/services/documentdb/) - DocumentDB is a fully managed NoSQL database service built for fast and predictable performance, high availability, elastic scaling.

### Search DB
- [Elasticsearch](https://www.elastic.co/products/elasticsearch) - Elasticsearch is a distributed, RESTful search and analytics engine capable of solving a growing number of use cases.
- [Apache Solr](https://lucene.apache.org/solr/) - Solr is highly reliable, scalable and fault tolerant, providing distributed indexing, replication and load-balanced querying.
- [Splunk](https://www.splunk.com/) - Splunk Inc. provides the leading platform for Operational Intelligence. Customers use Splunk to search, monitor, analyze and visualize machine data.

### Graph DB
- [Neo4j](https://neo4j.com/) - Neo4j is a graph database management system developed by Neo Technology, Inc.
- [Titan](http://titan.thinkaurelius.com/) - Titan is a scalable graph database optimized for storing and querying graphs containing hundreds of billions of vertices and edges distributed across clusters.
- [GraphX](http://spark.apache.org/graphx/) - GraphX is Apache Spark's API for graphs and graph-parallel computation, with a built-in library of common algorithms.

### NewSQL
- [NouDB](http://www.nuodb.com/) - NuoDB is a database startup company based in Cambridge, Massachusetts. It sells a NewSQL database that works in the cloud.
- [FoundationDB](http://www.foundationdb.com/) - FoundationDB was a multi-model NoSQL database with a shared nothing architecture.

### In-memory DB
- [Oracle Database In-Memory](https://www.oracle.com/database/database-in-memory/index.html) - Oracle Database In-Memory delivers leading-edge in-memory performance without the need to restrict functionality or accept compromises, complexity and risk.
- [DB2 BLU](http://www.ibmbluhub.com/) - BLU Acceleration is revolutionary in-memory technology that is designed for high-performance analytics and data-intensive reporting.
- [IBM dashDB](https://console.ng.bluemix.net/catalog/services/dashdb) - IBM dashDB offers fully-managed, SQL database services.
- [Hekaton](https://www.microsoft.com/en-us/research/publication/hekaton-sql-servers-memory-optimized-oltp-engine/) - Hekaton is a new database engine optimized for memory resident data and OLTP workloads.
- [Apache Kudu](http://kudu.apache.org/) - Apache Kudu completes Hadoop's storage layer to enable fast analytics on fast data.
- [Redis](http://redis.io/) - Redis is an open source (BSD licensed), in-memory data structure store, used as database, cache and message broker.
- [VoltDB](https://www.voltdb.com/) - VoltDB is the world's fastest in-memory operational database - allowing you to ingest data, analyze data, and act on data in milliseconds with real-time experience.
- [MemcacheDB](http://memcachedb.org/) - MemcacheDB is a distributed key-value storage system designed for persistent.
- [Pivotal GemFire](https://pivotal.io/big-data/pivotal-gemfire) - Pivotal GemFire is an in-memory distributed data grid for high scale custom applications.
- [Apache Geode](http://geode.apache.org/) - Apache Geode is a distributed, in-memory database with strong data consistency.
- [H2](http://www.h2database.com/) - H2 is a relational database management system written in Java. It can be embedded in Java applications or run in the client-server mode.
- [Hazelcast](https://hazelcast.com/) - Hazelcast is the leading in-memory data grid solution.
- [Ehcache](http://www.ehcache.org/) - Ehcache is an open source, standards-based cache that boosts performance, offloads your database, and simplifies scalability.
- [Infinispan](http://infinispan.org/) - Infinispan is a distributed cache and key-value NoSQL data store software developed by Red Hat.
- [GridGain](https://www.gridgain.com/) - The GridGain Enterprise Edition includes valuable features added to Apache® Ignite™ which make deploying and maintaining a high performance in-memory.
- [Apache Ignite](https://ignite.apache.org/) - Apache Ignitetm In-Memory Data Fabric is a high-performance, integrated and distributed in-memory platform for computing and transacting.
- [JCS](https://commons.apache.org/proper/commons-jcs/) - JCS is a distributed caching system written in Java.

### Event Store
- [Event Store](https://geteventstore.com/) - The open-source, functional database with Complex Event Processing in JavaScript.

### Embedded Database
- [RocksDB](http://rocksdb.org/) - RocksDB is an embeddable persistent key-value store for fast storage.
- [LevelDB](http://leveldb.org/) - LevelDB is a simple key/value data store built by Google, inspired by BigTable.
- [SQLite](https://sqlite.org/) - SQLite is a relational database management system contained in a C programming library.
- [Berkeley DB](http://www.oracle.com/technetwork/database/database-technologies/berkeleydb/overview/index.html) - Berkeley DB is a family of embedded key-value database libraries providing scalable high-performance data management services to applications.
- [JavaDB](http://www.oracle.com/technetwork/java/javadb/overview/index.html) - Java DB is Oracle's supported distribution of the Apache Derby open source database.
- [Apache Derby](https://db.apache.org/derby/) - Apache Derby, an Apache DB subproject, is an open source relational database implemented entirely in Java and available under the Apache License.

### Time Series
- [Riak TS](http://basho.com/products/riak-ts/) - Riak® TS is the only enterprise-grade NoSQL time series database optimized specifically for IoT and Time Series data.
- [InfluxDB](https://www.influxdata.com/) - InfluxDB is an open-source time series database developed by InfluxData as part of their time series platform. It is written in Go and optimized for fast. 

## Data Warehouse
- [Redshift](https://aws.amazon.com/documentation/redshift/) - Amazon Redshift is a fast, fully managed, petabyte-scale data warehouse service.
- [Vertica](http://www8.hp.com/us/en/software-solutions/advanced-sql-big-data-analytics/) - HPE Vertica 8 introduces a unified architecture and advanced in-database analytics capabilities that enable users to conduct sophisticated analysis at industry-leading scale and speed.
- [Pivotal Greenplum](https://pivotal.io/big-data/pivotal-greenplum) - Pivotal Greenplum is a commercial fully featured data warehouse powered by the open source Greenplum Database.
- [InfiniDB](http://infinidb.co/) - Column Database Accelerates Insights for Analytics, BI, and Data Warehouse.
- [Druid](http://druid.io/) - Druid supports fast aggregations and sub-second OLAP queries.

## Storage
- [Amazon Simple Storage Service (S3)](https://aws.amazon.com/s3/) - Amazon Simple Storage Service (Amazon S3), provides developers and IT teams with secure, durable, highly-scalable cloud storage.
- [Riak S2](http://basho.com/products/riak-s2/) - Riak® S2 is a highly available, scalable, easy-to-operate object storage software solution that’s optimized for holding videos, images, and other files.

## Distributed File System
- [DSEFS](https://docs.datastax.com/en/latest-dse/datastax_enterprise/ana/aboutDsefs.html) - DSEFS (DataStax Enterprise file system) is a new distributed file system within DataStax Enterprise.

## BI Tools
- [Tableau](https://www.tableau.com/) - Tableau is data visualization software.
- [Pentaho](http://www.pentaho.com/) - Pentaho's big data integration and analytics solutions turn information into insights to help your organization gain a competitive advantage.
- [Qlik](https://www.qlik.com/) - Qlik delivers Business Intelligence software for data visualization, guided analytics, embedded analytics and reporting to over 40000 customers worldwide.
- [Birt](http://www.eclipse.org/birt/about/) - BIRT is an open source software project that provides the BIRT technology platform to create data visualizations and reports.
- [JasperReports®](http://community.jaspersoft.com/) - The JasperReports Library is the world's most popular open source reporting engine.
- [SAS Visual Analytics](http://www.sas.com/en_us/software/business-intelligence/visual-analytics.html) - Robust reporting and mobile BI.
- [IBM Watson Analytics](https://watson.analytics.ibmcloud.com/product) - Watson Analytics guides analysis with automated data visualization and discovery so you can uncover insights on your own.

## Parallel Programming
- [Actor Model](https://en.wikipedia.org/wiki/Actor_model) - The actor model in computer science is a mathematical model of concurrent computation that treats "actors" as the universal primitives of concurrent computation.
- [Communicating sequential processes](https://en.wikipedia.org/wiki/Communicating_sequential_processes) - Communicating sequential processes (CSP) is a formal language for describing patterns of interaction in concurrent systems. It is a member of the family of mathematical theories of concurrency known as process algebras, or process calculi, based on message passing via channels.

## Frameworks & Tools

### Reactive Framework
- [Akka](http://akka.io/) - Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM.
- [Reactor](http://projectreactor.io/) - Reactor is a fully non-blocking foundation with efficient demand management.
- [ReactiveX](http://reactivex.io/) - ReactiveX is a combination of the best ideas from the Observer pattern, the Iterator pattern, and functional programming.
- [Erlang](https://www.erlang.org/) - Erlang is a programming language used to build massively scalable soft real-time systems with requirements on high availability.
- [Goroutines](https://gobyexample.com/goroutines) - A goroutine is a function that is capable of running concurrently with other functions.
- [Vert.x](http://vertx.io/) - Vert.x is a tool-kit for building reactive applications on the JVM.
- [Play Framework](https://www.playframework.com/) - Play Framework makes it easy to build web applications with Java & Scala. Play is based on a lightweight, stateless, web-friendly architecture. Built on Akka.
- [Spring Web Reactive](http://docs.spring.io/spring-framework/docs/5.0.0.M1/spring-framework-reference/html/web-reactive.html) - Reactive programming is about non-blocking applications that are asynchronous and event-driven and require a small number of threads to scale.

### Micoservices Framework
- [Lagom](http://www.lagomframework.com/) - Lagom is a framework for creating reactive microservice-based systems.
- [Play Framework](https://www.playframework.com/) - Play Framework makes it easy to build web applications with Java & Scala. Play is based on a lightweight, stateless, web-friendly architecture. Built on Akka.
- [Spring Boot](https://projects.spring.io/spring-boot/) - Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can "just run".
- [Dropwizard](http://www.dropwizard.io/) - Dropwizard is a Java framework for developing ops-friendly, high-performance, RESTful web services.
- [Sparkjava](http://sparkjava.com/) - Spark Framework - Create web applications in Java rapidly. Spark is a micro web framework that lets you focus on writing your code, not boilerplate code.

### Monitoring
- [Ganglia](http://ganglia.info/) - Ganglia is a scalable distributed monitoring system for high-performance computing systems such as clusters and Grids.
- [Nagios](https://www.nagios.org/) - Nagios provides enterprise-class Open Source IT monitoring, network monitoring, server and applications monitoring.
- [Datadog](https://www.datadoghq.com/) - See metrics from all of your apps, tools & services in one place with Datadog's cloud monitoring as a service solution.
- [New Relic](https://newrelic.com/) - A software analytics tool suite used by developers, ops, and software companies to understand how your applications are performing in development.
- [Perfino](https://www.ej-technologies.com/products/perfino/overview.html) - Perfino is a zero-overhead APM solution for monitoring Java application servers.
- [Sensu](https://sensuapp.org/) - Monitor servers, services, application health, and business KPIs.
- [OverOps](https://www.overops.com/) - Know why Java code fails in production.

### Load Balancer
- [HAProxy](http://www.haproxy.org/) - The Reliable, High Performance TCP/HTTP Load Balancer.

### API Gateway
- [Tyk](https://tyk.io/) - Tyk is an open source API Gateway that is fast, scalable and modern.
- [WSO2](http://wso2.com/) - WSO2 provides the open source enterprise platform that helps to build, integrate, analyse and manage your APIs, applications, and Web services.

### Testing Tools
- [JUnit](http://junit.org/) - JUnit is a simple framework to write repeatable tests.
- [Mockito](http://site.mockito.org/) - A mocking framework for unit tests written in Java.
- [TestNG](http://testng.org/) - TestNG is a testing framework developed in the lines of JUnit and NUnit.
- [DbUnit](http://dbunit.sourceforge.net/) - A JUnit extension that puts a database into a known state between test runs.
- [Selenium](http://docs.seleniumhq.org/) - Selenium is a suite of tools to automate web browsers across many platforms.
- [Cucumber](https://cucumber.io/) - Cucumber is a software tool that computer programmers use for testing other software.
- [SoapUI](https://www.soapui.org/) - SoapUI, is the world leading Open Source Functional Testing tool for API Testing.
- [LoadUI](https://www.loadui.org/) - LoadUI, a Performance Load Testing tool for APIs & Web Services.
- [Secure Pro](https://smartbear.com/product/ready-api/secure/overview/) - Simulate attacks against your REST and SOAP services so you know they're safe. Build a Trusted API with Secure Pro, Based on The world's Most Trusted API.

### Code Quality Analyzer
- [SonarQube](http://www.sonarqube.org/) - SonarQube is an open platform to manage code quality.
- [Gerrit](https://www.gerritcodereview.com/) - Gerrit provides web based code review and repository management for the Git version control system.
- [PMD](https://pmd.github.io/) - PMD is a source code analyzer.

### Code Security Analyzer
- [Checkmarx](https://www.checkmarx.com/) - Checkmarx is a provider of state-of-the-art application security solution: static code analysis software, seamlessly integrated into development process.

### SQL Database Version Manager
- [Flyway](https://flywaydb.org/) - Flyway lets you regain control of your database migrations with pleasure and plain sql.
- [Liquibase](http://www.liquibase.org/) - Liquibase is an open source database-independent library for tracking, managing and applying database schema changes. 
- [RedGate](http://www.red-gate.com/) - Redgate's DLM(Database Lifecycle Management) solution helps you put in place a trusted, scalable and repeatable database change management process.

### SMTP Server
- [Apache James](https://james.apache.org/) - The Apache Java Mail Server is a 100% pure Java SMTP, IMAP4 and POP3 Mail server designed to be a complete and portable enterprise mail. 

### Profiling Tools
- [JProfiler](https://www.ej-technologies.com/products/jprofiler/overview.html) - JProfiler is the leading Java Profiler for profiling on the JVM. 

## DevOps
- [Docker](https://www.docker.com/) - Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications, whether on laptops, data center VMs, or the cloud.
- [Ansible](https://www.ansible.com/) - Ansible is the simplest way to automate apps and IT infrastructure.
- [Jenkins](https://jenkins.io/) - Jenkins is an open source automation server written in Java.
- [Bamboo](https://www.atlassian.com/software/bamboo) - Continuous delivery, from code to deployment. ... Focus on coding and count on Bamboo as your CI and build server.
- [Chef](https://www.chef.io/chef/) - Chef is an open source software agent that automates your infrastructure by turning it into code.
- [Puppet](https://puppet.com/) - Puppet is an open-source configuration management tool.

## Security
- [OWASP](https://www.owasp.org/) - The Open Web Application Security Project (OWASP) is an online community which creates freely-available articles, methodologies, documentation, tools.
- [OAuth](https://oauth.net/) - OAuth is an open standard for authorization, commonly used as a way for Internet users to authorize websites or applications to access their information on other.
- [SAML](https://en.wikipedia.org/wiki/Security_Assertion_Markup_Language) - Security Assertion Markup Language (SAML, pronounced sam-el) is an XML-based, open-standard data format for exchanging authentication and authorization data.
- [MIT KDC](https://web.mit.edu/kerberos/krb5-devel/doc/admin/install_kdc.html) - Kerberos is a network authentication protocol. It is designed to provide strong authentication for client/server applications by using secret-key cryptography.
- [OpenLDAP](http://www.openldap.org/) - OpenLDAP Software is an open source implementation of the Lightweight Directory Access Protocol.
- [Active Directory](https://en.wikipedia.org/wiki/Active_Directory) - Active Directory (AD) is a directory service that Microsoft developed for Windows domain networks.

## Mobile Frameworks
- [Xamarin](https://www.xamarin.com/) - Xamarin's mobile application development platform with native user interfaces enables sharing of code across all platforms with a single C# codebase.
- [React Native](https://facebook.github.io/react-native/) - Build Native Mobile Apps using JavaScript and React. React Native lets you build mobile apps using only JavaScript. It uses the same design as React. 
- [Apache Cordova](https://cordova.apache.org/) - Apache Cordova (formerly PhoneGap) is a popular mobile application development framework originally created by Nitobi.

## Game Engines
- [Unity3D](https://unity3d.com/) - Unity3D is a cross-platform game engine developed by Unity Technologies and used to develop video games for PC, consoles, mobile devices and websites.
- [Unreal Engine](https://www.unrealengine.com) - Unreal Engine 4 is a suite of integrated tools for game developers to design and build games, simulations, and visualizations.

## AI Tools
- [IBM Watson](http://www.ibm.com/watson/) - IBM Watson is a technology platform that uses natural language processing and machine learning to reveal insights from large amounts of unstructured data.
- [OpenCV](http://opencv.org/) - OpenCV (Open Source Computer Vision) is a library of programming functions mainly aimed at real-time computer vision.

## IoT

### IoT OS
- [Brillo](https://developers.google.com/brillo/) - Brillo brings the simplicity and speed of software development to hardware for IoT with an embedded OS, core services, developer kit, and developer console.
- [mbed OS](https://www.mbed.com/en/platform/mbed-os/) - ARM mbed OS is a platform operating system designed for the internet of things.

## UML Tools
- [Draw.io](https://www.draw.io/) - Draw.io is free online diagram software for making flowcharts, process diagrams, org charts, UML, ER and network diagrams.
- [Microsoft Visio](https://products.office.com/en/visio/flowchart-software) - Microsoft Visio (formerly Microsoft Office Visio) is a diagramming and vector graphics application and is part of the Microsoft Office family.
- [Enterprise Architect](http://www.sparxsystems.com/) - Enterprise architects are practitioners of enterprise architecture; an enterprise strategic management discipline that operates within organizations.

## Summit Events
- [Web Summit](https://websummit.net/) - It's been called 'the best technology conference on the planet'.
- [AWS Summit](https://aws.amazon.com/summits/) - Whether you are new to the cloud or an experienced user, you will learn something new at an AWS Summit.
- [Gamescom](http://www.gamescom-cologne.com/) - Gamescom (stylized as gamescom) is a trade fair for video games held annually at the Koelnmesse in Cologne, North Rhine-Westphalia, Germany.
- [GDC](http://www.gdconf.com/) - An event designed to inform and educate game industry professionals on online multiplayer games, mobile and next generation game technologies.
- [Strata Hadoop World](http://www.stratahadoopworld.com/) - Strata Hadoop World. Where big data, cutting-edge data science, and new business fundamentals intersect–and merge.
- [Spark Summit](https://spark-summit.org/) - Organized by Databricks, Spark Summit is the premier big data conference series dedicated to bring the Apache Spark community together across the globe.
- [Reactive Summit](https://www.reactivesummit.org/) - Organized by Lightbend.

## Algorithms
- [Backtracking](https://en.wikipedia.org/wiki/Backtracking) - Backtracking is a general algorithm for finding all (or some) solutions to some computational problems. 

**[⬆ back to top](#table-of-contents)**

