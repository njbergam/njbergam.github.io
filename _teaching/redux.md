---
title: "Notes on Unsupervised Learning"
collection: teaching
type: "Independent Studies"
permalink: /teaching/redux
venue: "Verma Lab, Columbia University"
date: 2023-05-10
location: "New York, NY"
---

Unsupervised machine learning (UML) is about finding structure in unlabeled data: for instance, partitioning datapoints into groups or finding informative low-dimensional representations of high-dimensional datasets. Theory research in UML is largely concerned with developing algorithms with provable guarantees and establishing the complexity of UML objectives (e.g. density estimation, k-means clustering, manifold hypothesis testing).  


k-means, gradients, and smart initialization
======
<a href="kmeans_review.pdf">[Writeup] </a>
We discuss the classic k-means clustering problem from the perspective of gradient-based optimization. This is motivated by the fact that the popular Lloyd's method for k-means is equivalent to the Newton-Raphson method, and approximate versions of Lloyd's method are equivalent to stochastic gradient descent. In this writeup, we discuss Lloyd's method in the broader context of k-means hardness and approximability. We then provide a fleshed-out proof of the convergence of k-means++, an initialization scheme for Lloyd's algorithm which reduces its expected worst-case approximation ratio from unbounded to O(log k). 


Probably Approximate Johnson-Lindenstrass Lemma
======
<a href="jl.pdf">[Writeup] </a>
The Johnson-Lindenstrauss Lemma is a fundamental result in non-linear dimensionality reduction which shows that random projections of high-dimensional data happen to preserve pairwise distances. Usually this is formulated in terms of a lower bound on the number of dimensions we can project into. This lower bound is dependent on \(n\) (the number of points) and \(\epsilon\) (the tolerated amount of distortion in the embedding). In this writeup, we show a version of the lemma where the lower bound takes into account a user-provided \(\delta\) parameter, which specifies the probability with which a JL transform actually gives a good embedding.

