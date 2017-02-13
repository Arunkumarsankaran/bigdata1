1)various source of big data
types 
1.transaction
2.Social media
3.public data
4.sensor


2)3'v
1.volume
2.variety
3.velocity


3)Horizontal Scaling and Vertical Scaling
horizontal
Horizontal Scaling (Sharding): Horizontal scaling divides the data set and distributes the data over multiple servers, or shards. So, you can create 10 instance each with 1TB database. Each shard is an independent database, and collectively, the shards make up a single logical database.
vertical
Vertical Scaling: Suppose you have 10TB database in a mid size amazon machine instance.You can easily say that high query rates can exhaust your servers CPU power, can consume all of your RAM and sometimes you will find the working data set is exceeding your storage capacity.


4)Need and Working of Hadoop
Hadoop is an open source platform that provides excellent data management provision. It is a framework that supports the processing of large data sets in a distributed computing environment. It is designed to expand from single servers to thousands of machines, each providing computation and storage
It is quite expensive to build bigger servers with heavy configurations that handle large scale processing, but as an alternative, you can tie together many commodity computers with single-CPU, as a single functional distributed system and practically, the clustered machines can read the dataset in parallel and provide a much higher throughput. Moreover, it is cheaper than one high-end server. So this is the first motivational factor behind using Hadoop that it runs across clustered and low-cost machines.
