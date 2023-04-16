# Pyspark-Tutorial<br/>
**Pyspark** is a Python API for **Apache Spark**. <br/>
**Apache Spark** is an open-source analytics engine for large-scale data processing.<br/>

**History of Apache Spark**
To resolve the issue of **Big Data**, **Hadoop** was released.<br/>
**Hadoop** had three main parts -> **HDFS (Hadoop Distributed File System), Map Reduce (the computation engine) and YARN (Yet Another Resource Negotiator)**<br/>
Working of Hadoop -> There was a Master Node and multiple Slave Nodes. The process requests comes directly to the Master Node and is splitted across Slave Nodes for processing.<br/>
Later on Apache Spark was released. In **Apache Spark**, the computation engine is **Spark**.**Storage** can be **Local/HDFS/Amazon S3** and **Resource Manager** can be **YARN/MESOS/KUBERNETES**.<br/>

**PySpark Architecture**<br/>
Apache Spark works in a master-slave architecture where master is the driver and slaves are called workers. The entry point of the Spark Application 
starts with the creation of Spark Context by the driver. The resources are managed by the cluster manager. Cluster Manager is a platform where we can run a Spark Cluster.If we want to run a Spark Cluster on our computer or laptop, the Custer Manager can be mentioned as local.<br/>

Spark can be operated in two modes :- **Distributed** and **Standalone**<br/>
Distributed - If we use HDFS and YARN in Spark Cluster<br/>
Standalone -Simple cluster manager incorporated with Spark
<br/>
<br/>
Main features of Spark :- **In Memory Computation, Parallel Processing and Lazy Execution**<br/>
The main difference between Spark and Hadoop is that Spark is just a computation engine while Hadoop has Storage, Computation and Resource Manager.<br/>

**NOTE** :- Whenever working with a smaller dataset, python pandas can also be used. The main difference between pandas and pysaprk is that pandas is not distributed
that is it works on a single node.
