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

create keyspace saiashish with replication={'class':'SimpleStrategy','replication_factor':1}

use saiashish

CREATE TABLE User(
   id int PRIMARY KEY,
   name text,
   address text,
   age int
)

select * from User;
```

