
# Working with Cassandra using python

## Cassandra

* The Apache Cassandra database is the right choice when you need scalability and high availability without compromising performance. 
* Linear scalability and proven fault-tolerance on commodity hardware or cloud infrastructure make it the perfect platform for mission-critical data. 
* Cassandra's support for replicating across multiple datacenters is best-in-class, providing lower latency for your users and the peace of mind of knowing that you can survive regional outages.

**Major Companies which uses Cassandra**

Cassandra is in use at Activision, Apple, BazaarVoice, Best Buy, CERN, Constant Contact, Comcast, eBay, Fidelity, Github, Hulu, ING, Instagram, Intuit, Macy's™, Macquarie Bank, Microsoft, McDonalds, Netflix, New York Times, Outbrain, Pearson Education, Sky, Spotify, Uber, Walmart, and thousands of other companies that have large, active data sets. In fact, Cassandra is used by 40% of the Fortune 100.

### Top Features

**FAULT TOLERANT:** Data is automatically replicated to multiple nodes for fault-tolerance. Replication across multiple data centers is supported. Failed nodes can be replaced with no downtime.

**PERFORMANT:** Cassandra consistently outperforms popular NoSQL alternatives in benchmarks and real applications, primarily because of fundamental architectural choices.

**DECENTRALIZED:** There are no single points of failure. There are no network bottlenecks. Every node in the cluster is identical.

**SCALABLE:** Some of the largest production deployments include Apple's, with over 75,000 nodes storing over 10 PB of data, Netflix (2,500 nodes, 420 TB, over 1 trillion requests per day), Chinese search engine Easou (270 nodes, 300 TB, over 800 million requests per day), and eBay (over 100 nodes, 250 TB).

**DURABLE:** Cassandra is suitable for applications that can't afford to lose data, even when an entire data center goes down.

**YOU'RE IN CONTROL:** Choose between synchronous or asynchronous replication for each update. Highly available asynchronous operations are optimized with features like Hinted Handoff and Read Repair.

**ELASTIC:** Read and write throughput both increase linearly as new machines are added, with no downtime or interruption to applications.

**PROFESSIONALLY SUPPORTED:** Cassandra support contracts and services are available from third parties.

[More Information](https://cassandra.apache.org/doc/latest/)

# Description
Here i have tried to implement insert,update,delete and various other operations in Cassandra database using python.

I have used the cloud version of cassandra i.e  **DataStax Astra DB**
