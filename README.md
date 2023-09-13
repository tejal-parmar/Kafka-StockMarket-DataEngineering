# Stock Market Data Engineering using Kafka
End-to-end Data Engineering project on real time stock market data using Apache Kafka, Python and Amazon Web Services (AWS).

## Architecture
![Architecture](https://github.com/tejal-parmar/Kafka-StockMarket-DataEngineering/assets/111147531/936f2d7a-cc67-4a5b-9c49-03b2977222d5)

## Tools and Technologies
  - Python
  - Apache Kafka
  - Amazon Web Services (AWS)
      - S3 (Simple Storage Service)
      - Athena
      - Glue Crawler
      - Glue Catalog
      - EC2

## Dataset
Stock market dataset from Kaggle in csv format

## Apache Kafka
  - A real-time stream engine
  - A distributed event store and stream-processing platform

Events are distributed on different networks.
<br>
<b>Stream processing</b> is an act of performing continual calculation on potentially endless and constantly evolving source of data.

### Kafka Components
1. Producer : 
    - Produces the data, such as connected cars, sensors, financial transactions, hospital EMR, logistics shipping etc.
2. Broker : 
    - Single member server of Kafka cluster to write the data
    - Cluster is basically a group of different machines or nodes
    - One single node or server is called broker.
3. Consumer:
    - Consumer can consume data from broker.
4. ZooKeeper: 
    - A resource manager that makes sure all the servers are running properly
    - Manages access control list and security related details.
5. Topics:
    - Topics are logical buckets inside the Kafka broker
    - Streams of related messages in Kafka in a logical representation
    - Categorizes messages into groups
    - Developers define topics
    - There can be unlimited number of topics

### Terminology
1. <b>Stream</b> : unbounded sequence of ordered, immutable data
2. <b>Stream Processing</b> : continual calculations performed on one or more streams
3. <b>Immutable data</b> : data that cannot be changed once it has been created
4. <b>Event</b> : an immutable fact regarding something that has ocurred in our system
5. <b>Broker</b> : single member server of Kafka cluster
6. <b>Cluster</b> : a group of one or more Kafka brokers working together to satisfy Kafka production and consumption 
7. <b>Node</b> :a single computing instance that may be physical as in a server or in a data center, or virtual instance might be in AWS, GCP or Azure
8. <b>Zookeeper</b> : used by Kafka brokers to determine which broker is the leader of a given partition and topic, as well as track cluster membership and configuration for Kafka
9. <b>Data Partition</b> : Kafka topics consist of one or more partitions, a partition is a log which provides ordering guarantees for all of the data contained within it, partitions are chosen by hashing key values
