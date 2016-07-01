# YanCloud


### Info:

 Base Apache Hadoop 2.6.4
 
### Using

Select Hadoop from the Rancher Catalog. Common HDFS options and Yarn/MapReduce memory options are available to set. 

Once the values are set, and the cluster is deployed:

On the hosts running the following services you can access

* HDFS manager on: `namenode-primary:50070`.
* Yarn Resource manager is accessible via `yarn-resourcemanager:8088` 

Your default HDFS filesystem URL is hdfs://<namenode>:8020 (Only available on Rancher Network)

