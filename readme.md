
# Big Data Analysis with Scala and Spark
Course given by coursera https://www.coursera.org/learn/scala-spark-big-data/home/welcome
### About this course

Manipulating big data distributed over a cluster using functional concepts is rampant in industry, and is arguably one of the first widespread industrial uses of functional ideas. This is evidenced by the popularity of MapReduce and Hadoop, and most recently Apache Spark, a fast, in-memory distributed collections framework written in Scala. In this course, we'll see how the data parallel paradigm can be extended to the distributed case, using Spark throughout. We'll cover Spark's programming model in detail, being careful to understand how and when it differs from familiar programming models, like shared-memory parallel collections or sequential Scala collections. Through hands-on examples in Spark and Scala, we'll learn when important issues related to distribution like latency and network communication should be considered and how they can be addressed effectively for improved performanc



#### Learning outcomes: 
By the end of this course you will be able to

<ul>
<li> Read data from persistent storage and load it into Apache Spark</li>
<li> Manipulate data with Spark and Scala </li>
<li> Express algorithms for data analysis in a functional style </li>
<li> Recognize how to avoid shuffles and recomputation in Spark</li> 
</ul> 


###  [Week 1](https://github.com/htefera/Data-Analysis-with-Scala-and-Spark/tree/master/example)
#### Getting Started + Spark Basics
Get up and running with Scala on your computer. Complete an example assignment to familiarize yourself with our unique way of submitting assignments. In this week, we'll bridge the gap between data parallelism in the shared memory scenario (learned in the Parallel Programming course, prerequisite) and the distributed scenario. We'll look at important concerns that arise in distributed systems, like latency and failure. We'll go on to cover the basics of Spark, a functionally-oriented framework for big data processing in Scala. We'll end the first week by exercising what we learned about Spark by immediately getting our hands dirty analyzing a real-world data set.

### [Week 2](https://github.com/htefera/Data-Analysis-with-Scala-and-Spark/tree/master/wikipedia)

#### Reduction Operations & Distributed Key-Value Pairs
This week, we'll look at a special kind of RDD called pair RDDs. With this specialized kind of RDD in hand, we'll cover essential operations on large data sets, such as reductions and joins.
### [Week 3](https://github.com/htefera/Data-Analysis-with-Scala-and-Spark/tree/master/stackoverflow)
#### Partitioning and Shuffling
This week we'll look at some of the performance implications of using operations like joins. Is it possible to get the same result without having to pay for the overhead of moving data over the network? We'll answer this question by delving into how we can partition our data to achieve better data locality, in turn optimizing some of our Spark jobs.
### [Week 4](https://github.com/htefera/Data-Analysis-with-Scala-and-Spark/tree/master/timeusage)

#### Structured data: SQL, Dataframes, and Datasets
With our newfound understanding of the cost of data movement in a Spark job, and some experience optimizing jobs for data locality last week, this week we'll focus on how we can more easily achieve similar optimizations. Can structured data help us? We'll look at Spark SQL and its powerful optimizer which uses structure to apply impressive optimizations. We'll move on to cover DataFrames and Datasets, which give us a way to mix RDDs with the powerful automatic optimizations behind Spark SQL.




