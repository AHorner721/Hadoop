# Hadoop
Learn to use Hadoop on Ubuntu 18.04 

## What I Learned
Hadoop is an open source big data management system. It is used for fast and reliable data storage/processing.

Consists of 4 main components:
  1. HDFS
  2. MapReduce
  3. YARN
  4. Utilities
  
HDFS:
    Hadoop Distributed File System
    File system of hadoop framework.
    Designed to store and manage huge volumes of data efficiently.
    Due to the way HDFS operates it provides redundancy.

MapReduce:
   - It is a programming paradigm that enables massive scalability across hundreds or thousands of servers in a Hadoop cluster. The term "MapReduce" refers to two separate jobs first is the map job, which takes a set of data and converts it into another set of data, where individual elements are broken down into tuples. The reduce job takes the output from a map as input and combines those data tuples into a smaller set of tuples
  
YARN:
   - Yet Another Resource Negotiator. Cluster resource manager is used to reduce bottleneck from mapReduce version 1. 
   - Cluster resource manager splits Job Tracker in two parts: 
        1. Manages resources for applications
        2. Manages resources for job scheduling/queue.
           - Use to increase data analysis and scale resources according to client requirements.
           - Supports multiple ways of processing data, like interactive query on Apache Spark, and other processing engines.
    
Utilities:
   - Used to facilitate other components. (HDFS, MapReduce,YARN)
