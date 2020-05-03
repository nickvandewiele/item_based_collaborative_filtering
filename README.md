# Item-based Collaborative Filtering

Here, I explore item-based collaborative filtering (https://en.wikipedia.org/wiki/Collaborative_filtering), a technique used in recommender systems.

I implement a recommender system for movies, based on the MovieLens 100K dataset (https://grouplens.org/datasets/movielens/). Copy the dataset from http://files.grouplens.org/datasets/movielens/ml-100k.zip, and unzip it into a folder.

The implementation of the item-based collaborative filtering procedure is done using Pandas. Nevertheless, I based my implementation on the excellent Udemy course "Taming Big Data with Apache Spark and Python - Hands On!" by Frank Kane (https://www.udemy.com/course/taming-big-data-with-apache-spark-hands-on/). The motive to implement with Pandas the algorithm is to compare implementations with a library for distributed computing like Spark.

The 100K ratings dataset leads to roughly 20M rows after the self-join, and results in roughly 1M movie pairs, and fits 


A Jupyter Notebook (`recommender.ipynb`) explains the methodology and the followed steps. A more concise version in python can be found in `recommender.py`, and can be run from the command line:

`python recommender.py`