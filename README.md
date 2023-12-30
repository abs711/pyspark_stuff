# pyspark_stuff

## SparkContext vs SparkSession

| SparkContext | SparkSession |
| --- | --- |
| repr connection to a Spark Cluster | unified entry point for interacting with Spark |
| coordinates task execution across the cluster | combines functionalities of SparkContext, SQLContext, HiveContext, and StreamingContext |
| entry point in earlier Spark versions (1.x) | introduced in Spark 2.0 |
