# Apache Kafka: A Distributed Streaming Platform

## Introduction
Apache Kafka is an open source stream processing software which is used for the processing of the real time data which in turn is stored. It operates in between two parties/senders and receivers and forwards information on their behalf. It can process approximately trillions of data events within a single day.

### What is Apache Kafka?

Apache Kafka is a software that works under distributed streaming process. It is a publish-subscribe messaging system which let the exchanging of data between applications, servers and processors too. Apache Kafka was built at LinkedIn and later handed over to Apache Foundation. It is today, supported by Confluent in collaboration with the Apache Software Foundation. Apache Kafka has solved the indolent issue of message exchange of data between sender and receiver.

## Key Features

* **Low Latency**: Apache Kafka provides low latency value, that is, upto 10 milliseconds. It is because it has message which enables the consumers to consume that message at any time they want.
* **High Throughput**: Kafka can produce and consume more number of messages of high volume and high velocity because of low latency. This can be because Kafka can handle thousands of messages in a second. Some examples of such organizations are Uber where Kafka is used for loading a large amount of data.
* **Fault tolerance**: Kafka has one crucial aspect to be resistant of node/machine failure of within the cluster.
* **Durability**: Kafka has replication feature that ensures the data or messages will always be sticky for more on the cluster over the disk. This makes it durable.
* **Reduces the need for multiple integrations**: Every data that a producer writes to go through Kafka. Thus, in order to be connected to all the producing and consuming systems, we only require a single integration with Kafka that does it for us.
* **Easily accessible**: Since all our data is written to Kafka, it is easy to easily get hands on it for anyone.
* **Distributed System**: Apache Kafka has a distributed setup which is one of the reasons it can be scaled. The distributed system is broader than that of Sharding, and has two subcategories; Partitioning and replication.
* **Real-Time handling**: Apache Kafka is capable of processing real time big data pipeline. Creating the pipeline of real-time data requires processors, analytics, storage and the like.
Batch approach: In its essence, Kafka uses batch-like use cases. It can also function similarly to an ETL tool due to the feature that makes it store data.
* **Scalability**: The ability of Kafka to manage high volume messages qualify it as a scalable software product.

## Need of Apache Kafka

Apache Kafka is a software platform that has the following reasons which best fits to explain about Apache Kafka.

1. Apache Kafka designs have demonstrated a throughput of millions of data or messages per second.
2. Apache Kafka acts in the middle between the source system and the target system. Hence the source system data is passed to the Apache Kafka, where it asynchronous the data and the target system data is received from the Kafka.
3. Therefore Apache Kafka is a software which is having very high performance that is having really low latency value less than 10ms.
4. Apache Kafka has a sturdy structure which has explained certain oddity in the exchange of data.
5. Companies like NETFLIX, UBER, Walmart and more than thousands of such companies use Apache Kafka.
6. Apache Kafka has the ability to keep the fault-tolerance. fault tolerance definiton implies that at times a consumer serves the message that was produced successfully. However, the consumer does not process the message back because of backend database problem or there is a bug in the consumer code. In such few cases, the message cannot be consumed again by the consumer or the audience that was targeted. For this reason, Apache Kafka has been able to work on the solution by rewriting the data.
7. Learning Kafka is a good way to earn a living. Therefore, for those in a position to embark on elevatoring their income in the near future in the IT sector, they can learn.

## Kafka Architecture

- **Data Ecosystem**: It is necessary to note that several applications built to operate with Apache Kafka form an ecosystem. This ecosystem is made for processing the data. This system receives inputs in the form of applications that manifest data, while output is expressed in terms of a set or metrics, reports etc. The below diagram is a circulatory data ecosystem of Kafka.
- **Kafka Cluster**: Kafka cluster is a system made up of brokers, topics, and the partitions for each topic. Only the cluster is able to write data to the topic and it also reads it.
- **Producers**: A producer puts data/messages into a topic within the cluster. For min بصرفهlarge storage of data, different producers from within an application can send the data to the Kafka cluster.
- **Consumers**: A consumer is the one that reads or consumes messages posts from the Kafka cluster. One or several consumers could consume different kind of data from the cluster. The great part of Kafka is that every consumer understands where it has to consume the data.
- **Brokers**: In Kafka terms, a Kafka server is referred to as a broker. A broker is a person or an organization that links producers and consumers. If any producer wants to write data to the cluster, it is initiated in the Kafka server. All brokers lie within a Kafka cluster itself. Furthermore, one can be a multiple broker.

![image](https://github.com/user-attachments/assets/0481caec-ee08-4821-ad0c-244c3e1a99f0)
- **Topics**: It can be a conventional name or a title assigned to stand for a similar sort of information. Apache Kafka has the feature that is able to have more than one topic in the cluster. Every topic indicates various types of messages.
- **Partitions**: The data or the message is chopped into small units called partition. Every partition contains data that is associated with an offset value for the desired load. The data is always written in a sequence. We also have many partitioning opportunities with an infinite number of values for the offset. But it is not certain to which partition the part of the message to be written will go.
- **ZooKeeper**: A ZooKeeper is to store some information about Kafka cluster and the detail of the consumer client. It can manage brokers by having a list of them. Furthermore, a ZooKeeper has the duty of determining which of the partitions will be led. Whenever something like this happens: a broker die, new topics, etc., the ZooKeeper informs Apache Kafka about it. Originally, a ZooKeeper is expected to work with an odd count of the Kafka servers. Zookeeper has one master which is leader and writes to the database, and all the other are replicas or sub-leaders which only read the database. However, a user does not directly communicate with the Zookeeper, but it communicates with brokers. Literally, no Kafka server can operate without a zookeeper server. At the very least it will be necessary to run the zookeeper server.


# Real Time Examples:

1. **Netflix** :Implements Kafka for real time analysis of user activity. This makes the experience much better for Netflix and viewers since they can point viewers towards different shows and films. 
2. **Uber**: Uses Kafka for massive real-time data for billing purposes and geofencing, dynamic pricing application. 
3. **LinkedIn** :Kafka is used for monitoring user interactions and computer parameters. 

## Getting Started with Kafka

1. Go to the Apache Kafka website at kafka.apache.org/downloads
2. Under Binary downloads, select the latest version of Apache Kafka
3. Download the file and extract it to a directory of your choice 

# Conclusion

Today Apache Kafka has become the backbone of the real-time data feed and streaming applications. While deploying it has a distributed architecture, scalability, high throughput, and fault tolerance, it is a very effective tool when dealing with large amounts of data streams. Based on the overview of Kafka principles, architecture and most common applications, organizations can benefit from applying Kafka’s potential and achieve creation of sound, scalable and effective data pipelines. As the methods of data processing are evolving, Kafka remains an essential part of the modern data platform.

# References

- https://www.javatpoint.com/apache-kafka
- https://www.geeksforgeeks.org/apache-kafka/
- https://kafka.apache.org/

 
