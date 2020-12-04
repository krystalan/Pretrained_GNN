
# Pretrained GNN Paper List
其实总结不了很多，主要是想了解一下现有的图数据结构预训练方法。   
关于GNN的一些资料直接从[Shurrrn](https://github.com/shihuieduca)的repo中fork了，我光总结一下Pretrained-GNN-model   

| Paper | Conference | Highlights |
| :---: | :---: | :---: |
| [GPT-GNN: Generative Pre-Training of Graph Neural Networks](https://arxiv.org/abs/2006.15437) | KDD 2020 | |
| [Strategies for Pre-training Graph Neural Networks](https://openreview.net/forum?id=HJlWWJSFDH) | ICLR 2020 | |
| [Deep Graph Infomax](https://arxiv.org/abs/1809.10341) | ICLR 2019 | [TODO] 训练了一个结点编码器，最大化局部结点表示与池化图全局表示之间的互信息 |
| [metapath2vec: Scalable Representation Learning for Heterogeneous Networks](https://dl.acm.org/doi/10.1145/3097983.3098036) | KDD 2017 | [TODO] 基于随机游走 |
| [Network Embedding as Matrix Factorization: Unifying DeepWalk, LINE, PTE, and node2vec](https://arxiv.org/abs/1710.02971) | WSDM 2018 | [TODO] 基于随机游走 |
| [Inductive Representation Learning on Large Graphs](https://arxiv.org/abs/1706.02216) | NIPS 2017 | [TODO] `GraphSAGE` 预测结点的存在性，基于随机游走 | 
| [Variational Graph Auto-Encoders](https://arxiv.org/abs/1611.07308) | NIPS 2016 Workshop | [TODO] 预测结点的存在性（重构图结构） |
| [node2vec: Scalable Feature Learning for Networks](https://arxiv.org/abs/1607.00653) | KDD 2016 | [TODO] 基于随机游走局部信息 |
| [subgraph2vec: Learning Distributed Representations of Rooted Sub-graphs from Large Graphs](https://arxiv.org/abs/1606.08928) | KDD 2016 Workshop | [TODO] 探索了如何将结点表示泛化到不同的任务中 |
| [LINE: Large-scale Information Network Embedding](https://arxiv.org/abs/1503.03578) | WWW 2015 | [TODO] 基于随机游走局部信息 |
| [DeepWalk: online learning of social representations](https://arxiv.org/abs/1403.6652) | KDD 2014 | [TODO] 基于随机游走局部信息 |
| [Heterogeneous Graph Transformer](https://dl.acm.org/doi/10.1145/3366423.3380027) | WWW 2020 | [TODO] 这篇不是预训练GNN工作，但我觉得挺有意思的，就放上来了，有空再读读 |



