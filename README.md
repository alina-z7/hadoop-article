# Hadoop

## What's Hadoop?

Hadoop is a software framework for a dataware house that is built from Apache developed in the United States.
It was mainly written in Java with its programming model MapReduce that can be written in any language

To learn more, visit the official [site](https://hadoop.apache.org): 

More Resources:  
[Wiki](https://simple.wikipedia.org/wiki/Apache_Hadoop) | [Official Docs](https://hadoop.apache.org/docs/current/) | [GitHub](https://github.com/apache/hadoop)

## Brief Overview

- Systems Embedded:
    - HDFS (core storage layer)
    - MapReduce (processing framework)
    - YARN
- Systems Inspired By:
    - Google File System
    - Google MapReduce
- Systems Compatible With:
    - Apache Hive (SQL-like interface)
    - Apache HBase (column-family store on HDFS)
    - Apache Spark (can run on Hadoop/YARN)

## History

Hadoop came out of the same general problem space that companies like Google were dealing with early on, how to store and process massive amounts of search and web data across lots of machines. Back then, traditional databases just did not scale well enough for that kind of workload. Google solved this internally with systems like MapReduce and the Google File System, but those were not publicly available.

That is where Hadoop comes in. It started it off in 2002 with Doug Cutting and Mike Cafarella as they were working on the Apache Nutch project. Around 2008, Hadoop was released as an open source project from Yahoo! when Doug Cutting joined. He took the ideas from Google’s MapReduce paper, originally published by Google engineers, and built an open source implementation with Apache Software Foundation (ASF) that anyone could use which was officially released in 2012. But it did not stop at just copying MapReduce, it turned into a full ecosystem that engineers could actually build on and extend and is maintained til today by the ASF.

At its core, Hadoop is made up of a few fundemental components. HDFS, the Hadoop Distributed File System, handles storage by splitting data across multiple machines and replicating it for fault tolerance. Then you have YARN, which manages cluster resources and schedules jobs so everything runs efficiently across nodes. On top of that foundation, a whole set of tools grew over time, like Hive for SQL like queries, Pig for dataflow scripting, and HBase for NoSQL style access. These tools made Hadoop much more practical for real world use, especially for companies that did not want to build everything from scratch.

Instead of being locked inside a company like Google, Hadoop gave regular organizations a way to run large scale distributed data processing on their own hardware. That made big data infrastructure accessible to a much wider range of engineers and businesses, and it is a big reason why the whole big data movement took off the way it did.

## Technical Specs

- Operating Systems: all OS compatible with JVM (MacOs/Linux/Windows)
- Supported Languages: Java, and other strongly-typed languages with supported environments
- License: Apache Lisense 2.0
- Written in: Java, w/ minor C/C++ componenets

## Features


#### Checkpoints
#### Compression
#### Concurrency Control
#### Data Model
#### Foreign Keys
#### Hardware Acceleration
#### Indexes
#### Isolation Levels
#### Joins
#### Logging
#### Parallel Execution
#### Query Compilation
#### Query Execution
#### Query Interface
#### Storage Architecture
#### Storage Format
#### Storage Model
#### Storage Organization
#### Stored Procedures
#### System Architecture
#### Views


### Sources

1. Apache Hadoop. “MapReduce Tutorial – Prerequisites.” Available at: https://hadoop.apache.org/docs/r1.2.1/mapred_tutorial.html#Prerequisites
2. Apache Hadoop. “HDFS Architecture Guide.” Available at: https://hadoop.apache.org/docs/r1.2.1/hdfs_design.html
3. Apache Hadoop. “Apache Hadoop YARN.” Available at: https://hadoop.apache.org/docs/stable/hadoop-yarn/hadoop-yarn-site/YARN.html
4. Dean, J., & Ghemawat, S. MapReduce: Simplified Data Processing on Large Clusters.
5. Google Cloud. “What is Hadoop?” Available at: https://cloud.google.com/learn/what-is-hadoop
6. IBM. “Hadoop vs. Spark.” Available at: https://www.ibm.com/think/insights/hadoop-vs-spark

