# Big-data-computing
Homeworks carried out for the Big Data Computing course I took for my master's degree.

There were three assignments to familiarize ourselves with PySpark in the context of Big Data: The first two were related to MapReduce algorithms and the third focused on the Spark Streaming API. The homework statements and the code templates were given by the course professors during the first semester of 2023.

## Homework 1:
In this case, the task was to implement two MapReduce algorithms, one using the Spark partitions and the other using a partition determined by a hash function. The goal was to approximate the count of distinct triangles in an undirected graph. The triangle-counting primitive is valuable in various scenarios, including social network analysis and web spam detection. For this initial assignment, we were instructed to run the algorithms locally.

## Homework 2:
This assignment built upon the work of homework 1 as it required a performance comparison between one of the algorithms that approximated the count and a different MapReduce algorithm that provided the exact count. Additionally, in this case, we were required to run the code with larger datasets than before (the [Orkut social network data](https://snap.stanford.edu/data/com-Orkut.html) with 117 million edges), utilizing the CloudVeneto cluster, a cloud infrastructure provided by the university.

## Homework 3:
The final assignment involved using the Spark Streaming API to process a continuous stream of integer items. This was achieved by implementing a space-efficient data structure called a count-sketch, which approximated the individual frequencies of the items and the second moment of the stream. Such practices are valuable for gathering statistics from applications that generate large volumes of data streams, such as online auctions and the Internet of Things.