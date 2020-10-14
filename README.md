# Hadoop_Tasks4.2
According to popular articles, Hadoop uses the concept of parallelism to upload the split data while fulfilling Velocity problem . (A myth) 
Lately, I came to know about this myth related to Hadoop which people tend to believe till date.

When a client uploads data, the date is uploaded in blocks, Serially (and not in parallels), with having block size (By default) : 64 MB and replication size: 3.

With this video I've shown this process.

Block size: 20 KB

Replication size: 2



Also, it is important for us to know that when block size decreases, the time taken to upload a file increases as the concept of series to upload the data is followed.

