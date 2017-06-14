# Neural Collaborative Filtering and Biased Matrix Factorization

Neural Collaborative Filtering can be seen as a generalization of biased Matrix Factorization.

## Introduction

Collaborative filtering (CF) is a well-performed model assumption in rating-based recommender systems.
In the recent decade, matrix factorization (MF) and its extensions (Biased MF, bayesian personalized ranking (BPR), factorization machines (FM), etc.) are popular implementations of CF.

In conference WWW 2017, Neural Collaborative Filtering (NCF) is proposed to model collaborative filtering by deep neural networks.
It combines the generalized matrix factorization (GMF) part and the multi-layer perceptron (MLP) part to get higher performance than previous MF-based approaches.
Here I show that NCF can be viewed as a generalization, or an extension, of biased MF.
It helps me understand why MCF may achieve a superior performance.
