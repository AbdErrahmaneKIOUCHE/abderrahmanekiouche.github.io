---
title: Graph Deep Learning
summary: M2 Data Sience
date: 2023-10-24
type: docs
math: false
tags:
  - Deep Learning
---
This course provides an in-depth exploration into the emerging field of graph deep learning, focusing on techniques to represent and analyze graph-structured data. It is designed for M2 Data Science students and covers both theoretical foundations and practical implementations.

## Course Overview

### Shallow Embedding Techniques
- **Introduction to Shallow Embeddings:**  
  Learn how to obtain vector representations of nodes in a graph using methods that capture the local and global structure of networks.
- **node2vec:**  
  Explore the node2vec algorithm, a scalable approach for feature learning on networks. This method allows for effective embedding of graph nodes by balancing between breadth-first and depth-first search strategies.  
  [Read more on node2vec](https://cs.stanford.edu/~jure/pubs/node2vec-kdd16.pdf) :contentReference[oaicite:0]{index=0}

### Graph Neural Networks (GNNs)
- **Introduction to GNNs:**  
  Delve into Graph Neural Networks, which extend deep learning methods to graph data by aggregating information from a node's neighbors.
- **Advanced Architectures:**  
  Study various GNN architectures and techniques for tasks such as node classification, link prediction, and graph clustering.  
  [Explore GNN research](https://arxiv.org/abs/1812.08434) :contentReference[oaicite:1]{index=1}

### Practical Applications
- **Real-World Use Cases:**  
  Apply graph deep learning techniques in various domains including social network analysis, recommendation systems, and biological networks.
- **Hands-on Projects:**  
  Engage in projects that integrate theoretical concepts with practical coding exercises using popular graph data analysis libraries.  
  [Additional resource](https://www.cs.mcgill.ca/~wlh/grl.html) :contentReference[oaicite:2]{index=2}

## Learning Outcomes

By the end of the course, students will be able to:
- **Apply Shallow Embedding Methods:**  
  Utilize techniques such as node2vec to extract meaningful features from graph data.
- **Design and Implement GNNs:**  
  Build and train Graph Neural Networks for various graph-related tasks.
- **Critically Evaluate Research:**  
  Analyze and assess the latest advancements in graph deep learning.
- **Integrate Theory with Practice:**  
  Combine theoretical insights with practical coding skills in real-world applications.

This comprehensive course is ideal for students aiming to deepen their expertise in deep learning and data science, with a specialized focus on graph-based methods that are increasingly pivotal in today's data-driven landscape.

## References

- [Grover, A. & Leskovec, J. (2016). node2vec: Scalable Feature Learning for Networks](https://cs.stanford.edu/~jure/pubs/node2vec-kdd16.pdf) :contentReference[oaicite:3]{index=3}
- [Zhou, J., et al. (2018). Graph Neural Networks: A Review of Methods and Applications](https://arxiv.org/abs/1812.08434) :contentReference[oaicite:4]{index=4}
- [Hamilton, W. (2017). Representation Learning on Graphs: Methods and Applications](https://www.cs.mcgill.ca/~wlh/grl.html) :contentReference[oaicite:5]{index=5}