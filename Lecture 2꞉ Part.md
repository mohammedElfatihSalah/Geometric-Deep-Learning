---
tags: [FML, GDL]
title: 'Lecture 2: Part (1)'
created: '2021-09-20T11:50:00.258Z'
modified: '2021-09-20T22:33:59.815Z'
---

# Lecture 2: Part (1)

## Statistical Learning in a nutshell

Today I am going to talk about statistical learning, what is high-dimensional and what are the challenges that faces learning in high dimensional setting. This is the first part of the lecture 2 in Geometric Deep Learning which you can find it [here](https://www.youtube.com/watch?v=pNks-HVVPcI). 

So what's statistical learning? **Statistical learning theory** is a framework for machine learning drawing from the fields of statistics and functional analysis. Statistical learning theory deals with the problem of finding a predictive function based on data. Statistical learning theory has led to successful applications in fields such as computer vision, speech recognition, and bioinformatics [1]. A good definition, but probably you are still confused how it actually works, so in a nutshell **Statistical learning** has four components if you understand them, you know what is statistical learning, those components are:

- Data Distribution.
- Approximation Model.
- Error Metric.
- Estimation Algorithm.

### Data Distribution

Data is the set of samples $\{(x_i,y_i)\}_{i=1 to N}$ where:
- $x_i$ is the input features, Also we assume $x_i \sim v$ where $v$ is a data distribution.
- $y_i$ is the output that we want to predict, where $y_i = f^*(x_i)$, and assume for now $y_i \in R$

we want to find $f^*$ given the samples only, without knowing the distribution $v$.

### Approximation Model


As said above given the samples above we need to find $f^*$, to search for this function we need to put assumption on it, that specifying a hypothesis class for it, but what is **hypothesis class**? 

**hypothesis class** is a set of functions that has the same characteristic, i.e the set of polynomial function, neural networks of given architecture..etc.

We need to assume a hypothesis class for $f^*$

Mathematically a hypothesis classc $F$

## Further reading

## References
[1] Trevor Hastie, Robert Tibshirani, Jerome Friedman (2009) The Elements of Statistical Learning, Springer-Verlag
