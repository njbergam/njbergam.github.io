---
title: "Lectures for the Undergraduate Math Society"
collection: teaching
type: "Club"
permalink: /teaching/ums
venue: "Columbia Undergraduate Math Society"
date: 2023-08-22
location: "New York, NY"
---

I have given a number of lectures to the Undergraduate Math Society, on topics ranging from topological data analysis to combinatorics to spectral graph theory. Here are some lecture notes and slides.

Learning (and Sleeping!?) with Experts and Bandits
======
<a href="experts.pdf">[Handwritten Notes] </a>
Online learning is a framework in machine learning where data becomes available in sequential order (think stock prices, time series, or any sort of time series type of data) and the learner must make predictions using this sequence. The goal is to minimize“regret”, i.e. the difference between the error of the learner and the error of the best course of predictions in hindsight. In this talk, we discuss two classical online learning problems: online allocation (where the loss of all actions is revealed each day, in the spirit of “full information”) and multi-armed bandits (where only the loss of the chosen action is revealed each day; “partial information”). Time permitting, we introduce the sleeping experts problem which presents an added layer of complexity to the idea of online learning with partial information. We develop a new algorithm for this sleeping.


Approximating k-means
======
<a href="ums5_kmeans.pdf">[Handwritten Notes] </a>
k-means is the mother of all clustering problems: given n points in d-dimensional Euclidean space, find k "cluster-centers" such that the sum of squared distances from each point to its closest cluster center is minimized. k-means is an NP-hard optimization problem for d>1, so it is not expected that k-means admits an exact algorithm. There is, however, a popular and practical algorithm for k-means known as LLoyd's method. We show how Lloyd's method can be badly behaved in certain settings, but with the right initialization ("k-means++", cf. Arthur and Vassilvitskii 2007), lends itself to an O(log k)-approximation algorithm (in fact, constant-factor for well-clustered data). 


The Duality of Trace and Determinant
======
<a href="ums4.pdf">[Presentation] </a>
The exterior product and the k-linear extension provide us with a very elegant way to relate the trace and determinant (and envision some of the other matrix invariants that lie "in between'' them). In this presentation, we further explore the relationship between trace and determinant through the lens of two famous theorems: Liouville's identity and Jacobi's formula. We sketch the proofs of both results using formal power series, following Winitzki §4.5.


t-SNE's spectral regime
======
<a href="ums_tsne.pdf">[Presentation] </a>
t-distibuted stochastic neighbor embedding (Van der Maaten 2008) is popular method for data visualization. Recent results have rigorously established that t-SNE optimized with gradient descent is effective at visualizing cluster structure in high-dimensional data. In this talk, we introduce one of the leading theoretical models for understanding t-SNE (and what it might be missing). This model, developed by Cai and Ma (2022),unveils how, under certain conditions, t-SNE approximates a classical dimensionality reduction technique known as spectral clustering.   


Coins, Partitions, and Generating Functions
======
<a href="ums2.pdf">[Notes] </a> 
<a href="https://www.youtube.com/watch?v=3llKS5i7vV8&t=2041s&ab_channel=NoahBergam">[Video] </a> 
How many ways are there to change a dollar into pennies, nickels, quarters, and dimes? How quickly can we figure it out? These questions and their immediate generalizations take us on a fascinating tour of combinatorics. In this talk, we analyze the change-making problem using generating functions, and we use our method to motivate the theory of counting partitions (where a partition is simply an arrangement of n objects into k distinct piles). In developing this theory, we arrive at powerful results such as Euler's Pentagonal Number Theorem and Hardy and Ramanujan's asymptotic formula for the partition function.





Topological Insights on Vector-Embedded Language
======
<a href="ums1.pdf">[Presentation] </a>
Topological data analysis (TDA), in contrast with more traditional statistical methods, allows us to quantify the shape and effectively reduce the dimensionality of high-dimensional, nonlinear data. In this project, we use TDA to enhance a simple linear regression model aimed at automated author classification. Motivated by
previous applications of TDA to time series data, we collect topological metrics of the sequence of word embeddings and use these as features. We find that these TDA-driven metrics outdo more direct statistical analyses of the word embeddings such as max or sum pooling. This project sheds light into benefits of incorporating TDA into the natural language processing and general machine learning pipeline.

