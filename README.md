# Spark-a-little
Spark seems to be an overkill for simple projects.
However, small projects often very quickly outgrow the laptop.
Avoid the pain of scaling up.

###Why Spark?
- Spark operates on Resilent Distributed Datasets (RDDs) that can be used to represent data tables.
- The same code for local environment (laptop) and cluster.
- Spark's concept of "transformations" (e.g. "map") and "actions" (e.g. "reduce") makes it easy to wirte parallel programs.
- A lot of the ETL work can be taken care of in fairly intuitive ways.
- Spark + Hive supports SQL queries on data tables. Sometimes, SQL offers the most elegant way.
- Spark has it's own machine learning library
- In local mode Spark reads from regular file system; on the cluster it usually reads from HDFS.

