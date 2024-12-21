# Project files on Intelligent Data Labeling via Neural Network-Driven Active Learning for Enhanced Model Efficiency

The repository consists of Jupyter notebooks that were used to for this project, dealing with the MNIST and CIFAR-10 datasets.

## Abstract

In this report learning methods for improving data labeling work flows is explored. This includes both active learning methods like querying strategies for selecting samples for the oracle to label. A hybrid approach combining uncertainty estimation with diversity is proposed to refine sample selection. Bayesian neural networks employing Monte Carlo sampling are utilized to address overconfidence issues when using uncertainty as a query. The concept of pseudo-labeling is explored as a potential means of expanding labeled datasets without manual intervention. Experimental evaluations on MNIST suggest that random sampling performs comparably in high-quality datasets, with simpler query-strategies like margin and entropy performing worse. Laplace approximation showed some promising results. It is theorized that combining pseudo-labeling with active learning, particularly entropy-based querying and Laplace approximation, could enhance performance and efficiency in lower-quality datasets.
