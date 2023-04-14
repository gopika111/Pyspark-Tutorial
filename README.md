# Pyspark-Tutorial<br/>

To resolve the issue of **Big Data**, **Hadoop** was released.<br/>
**Hadoop** had three main parts -> **HDFS (Hadoop Distributed File System), Map Reduce (the computation engine) and YARN (Yet Another Resource Negotiator)**<br/>
Working of Hadoop -> There was a Master Node and multiple Slave Nodes. The process requests comes directly to the Master Node and is splitted across Slave Nodes for processing.<br/>
Later on Apache Spark was released. In **Apache Spark**, the computation engine is **Spark**.**Storage** can be **Local/HDFS/Amazon S3** and **Resource Manager** can be **YARN/MESOS/KUBERNETES**.
Spark can be operated in two modes :- **Distributed** and **Standalone**
Distributed - If we use HDFS and YARN is Spark Cluster
Standalone - If we do not use HDFS and YARN is Spark Cluster
<br/>
<br/>
Main features of Spark :- **In Memory Computation, Parallel Processing and Lazy Execution**<br/>
The main difference between Spark and Hadoop is that Spark is just a computation engine while Hadoop has Storage, Computation and Resource Manager.<br/>
