# CGIPool
This repository contains the implementation of CGIPool presented in the following paper:
>Yunsheng Pang, Yunxiang Zhao, Dongsheng Li. "Graph Pooling via Coarsened Graph Infomax" (SIGIR 2021). [https://arxiv.org/abs/2105.01275](https://arxiv.org/abs/2105.01275)

### Introduction
![CGIPool](figures/CGIPool.jpeg)
Graph pooling that summaries the information in a large graph into a compact form is essential in hierarchical graph representation learning. Existing graph pooling methods either suffer from high computational complexity or cannot capture the global dependencies between graphs before and after pooling. To address the problems of existing graph pooling methods, we propose Coarsened Graph Infomax Pooling (CGIPool) that maximizes the mutual information between the input and the coarsened graph of each pooling layer to preserve graph-level dependencies. To achieve mutual information neural maximization, we apply contrastive learning and propose a self-attention-based algorithm for learning positive and negative samples. Extensive experimental results on seven datasets illustrate the superiority of CGIPool comparing to the state-of-the-art methods.
