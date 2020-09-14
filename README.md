# Delta Lake Examples
Delta Lake is an open-source storage layer that brings ACID transactions to Apache Spark™ and big data workloads. This repo provides working code for the examples of Delta Lake
### Install Apache Spark
https://archive.apache.org/dist/spark/
#### Install parquet-tools (Optional), will be helpful to analyse parquet file
pip3 install parquet-tools

parquet-tools inspect ${parquet_file} -> to get metadata of parquet file

### Python Spark(PySpark) with delta dependency
pyspark --packages io.delta:delta-core_2.11:0.3.0

### Scala Spark Shell with delta dependency
spark-shell --packages io.delta:delta-core_2.11:0.3.0

#### References: 
https://delta.io/

https://www.learningjournal.guru/

DataSets are downloaded from kaggle and updated to mock the scenario's
