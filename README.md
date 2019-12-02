# Parallel Computing for Machine Learning
### Machine learning, in general, is a statiscal approach to identify latent governing patterns in large datasets and make new discoveries with the uncovered patterns. However, the Internet today produces vast amount of data every second, and processing such enormous data with machine learning in real time is beyond the capibility of any single CPU human has created.
### One way to address the above issue is to utilize high performance distributed computing technique. Based on the idea of divide & conquer, if we can break the standard machine learning problem into smaller and more manageable independent jobs, we will be able to complete the task quickly in a parallel fasion.

### In this project, we explore a large family of machine learning algorithms, including supervised learning such as linear regression, logistic regression, random forrest, as well as unsupervised k-means clustering method. Our goal is to realize these algorithms using a popular parallel computing framework, i.e. Apache Spark.

# Distributed algorithms for machine learning

### Parallel computing framework we will use for this project is Apache Spark. The following figure illustrates how it works.
<img src="./pics/figure_1.png" />

### Based on Apache Spark, we hope to realize distributed Machine Learning algorithms on multi-core, in order to take advantage of the massive computing power of modern computers and thus speed the learning process. The following shows 3 learning examples: linear regression, logistic regression and random forest.

### Example 1: how parallel linear regression works.

<img src="./pics/figure_2.png" />

## Example 2: how paralle logistic regression works.

<img src="./pics/figure_3.png" />

## Example 3: how paralle random forest works.

<img src="./pics/figure_4.png" />

# Expected results
### we expect to parallelize a large class of machine learning algorithms on multicore processors, and find how much these learning algorithms can be improved in terms of running time.

# What's next?

# References:
### 1.
### 2.
