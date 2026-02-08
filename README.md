# Adaptive-K-Means-Clustering-Using-K-Means-and-Q-Learning
This project explores unsupervised image clustering on CIFAR-10 using deep features extracted from a pretrained ResNet-18. Instead of manually choosing the number of clusters or the CNN layer, a Q-learning reinforcement learning agent is used to automatically optimize these parameters.

The agent learns to select:
-the number of clusters (K) for K-Means
-the CNN layer used for feature extraction

based on clustering quality metrics such as Silhouette Score and Normalized Mutual Information (NMI).

This approach demonstrates how reinforcement learning can be combined with deep feature extraction to adaptively improve unsupervised clustering performance.
