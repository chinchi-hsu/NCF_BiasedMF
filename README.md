# Neural Collaborative Filtering and Biased Matrix Factorization

Neural Collaborative Filtering can be seen as a generalization of biased Matrix Factorization.

## Introduction

Collaborative Filtering (CF) is a well-performed model assumption for rating-based recommender systems.
In the recent decade, Matrix Factorization (MF) and its extensions (Bayesian Personalized Ranking (BPR), Factorization Machines (FM), etc.) are popular implementations of CF.

In conference WWW 2017, Neural Collaborative Filtering (NCF) is proposed to model collaborative filtering by deep neural networks.
It combines the generalized matrix factorization (GMF) part and the multi-layer perceptron (MLP) part to outperform previous MF-based approaches.
Here I show that NCF can be viewed as a generalization, or an extension, of biased MF.
It helps me understand NCF more deeply.

## References

Koren, Yehuda, Robert Bell, and Chris Volinsky. "Matrix factorization techniques for recommender systems." Computer 42.8 (2009).

He, Xiangnan, et al. "Neural collaborative filtering." Proceedings of the 26th International Conference on World Wide Web. International World Wide Web Conferences Steering Committee, 2017.
