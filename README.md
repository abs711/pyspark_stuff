# pyspark_stuff

## SparkContext vs SparkSession

| SparkContext | SparkSession |
| --- | --- |
| repr connection to a Spark Cluster | unified entry point for interacting with Spark, introduced in Spark 2.0 |
| coordinates task execution across the cluster | combines functionalities of SparkContext, SQLContext, HiveContext, and StreamingContext |
| entry point in earlier Spark versions (1.x) | supports multiple programming languages (Scala, Java, Python, R) |
