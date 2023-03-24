```
Installation Link:
```

http://downloads.datastax.com/community/datastax-community-64bit_3.0.9.msi

https://cassandra.apache.org/_/index.html

https://en.wikipedia.org/wiki/Apache_Cassandra

https://www.datastax.com/blog/working-apache-cassandra-mac-os-x

```
Open Source NoSQL Database
Manage massive amounts of data, fast, without losing sleep

Apache Cassandra is an open source NoSQL distributed database trusted by thousands of companies 
for scalability and high availability without compromising performance. 
Linear scalability and proven fault-tolerance on commodity hardware or
cloud infrastructure make it the perfect platform for mission-critical data.

Cassandra is a free and open-source, distributed, wide-column store,
NoSQL database management system designed to handle large amounts of data across
many commodity servers, providing high availability with no single point of failure.
Cassandra offers support for clusters spanning multiple datacenters, with asynchronous
masterless replication allowing low latency operations for all clients. Cassandra
was designed to implement a combination of Amazon's Dynamo distributed storage 
and replication techniques combined with Google's Bigtable data 
and storage engine model.
```


https://www.tutorialspoint.com/cassandra/cassandra_introduction.htm

```
Besides Cassandra, we have the following NoSQL databases that are quite popular −

Apache HBase − HBase is an open source, non-relational, distributed database
modeled after Google’s BigTable and is written in Java. It is developed as a part 
of Apache Hadoop project and runs on top of HDFS, providing BigTable-like capabilities
for Hadoop.

MongoDB − MongoDB is a cross-platform document-oriented database system that avoids 
using the traditional table-based relational database structure in favor of JSON-like
documents with dynamic schemas making the integration of data in certain types
of applications easier and faster.

CQL means cassandra query language.

keyspace of cassandra is just like schema of mongodb
```

```
https://downloads.datastax.com/#enterprise
tar -xzf dse-6.8.33-bin.tar.gz 
cd dse-6.8.33/resources/cassandra/bin
sudo ./cassandra -R

./cqlsh

brew install cassandra
cassandra -f 
(foreground)
cqlsh

create keyspace saiashish with replication={'class':'SimpleStrategy','replication_factor':1};

use saiashish;

CREATE TABLE User(
   id int PRIMARY KEY,
   name text,
   address text,
   age int
);

select * from User;
```

<img width="563" alt="Screenshot 2023-03-24 at 10 24 44 PM" src="https://user-images.githubusercontent.com/43849911/227590604-533155a4-ee16-4361-9e87-ae2c36389373.png">

<img width="683" alt="Screenshot 2023-03-24 at 10 25 37 PM" src="https://user-images.githubusercontent.com/43849911/227590789-d0a4e212-d35b-40b2-bcbf-6e2c07522093.png">

<img width="951" alt="Screenshot 2023-03-24 at 10 26 42 PM" src="https://user-images.githubusercontent.com/43849911/227591037-e1aff44e-4a26-41af-aa04-4d8569402dad.png">

<img width="887" alt="Screenshot 2023-03-24 at 10 27 19 PM" src="https://user-images.githubusercontent.com/43849911/227591197-e02de609-434c-429f-aa75-b56994cbe530.png">

<img width="620" alt="Screenshot 2023-03-24 at 10 28 14 PM" src="https://user-images.githubusercontent.com/43849911/227591430-ca8b806a-6dd3-44b1-ae15-73c747b7e849.png">
