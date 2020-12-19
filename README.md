
# Pretrained GNN Paper List
其实总结不了很多，主要是想了解一下现有的图数据结构预训练方法。   
关于GNN的一些资料直接从[Shurrrn](https://github.com/shihuieduca)的repo中fork了，我光总结一下Pretrained-GNN-model   

| Paper | Conference | Highlights |
| :---: | :---: | :---: |
| Learning to Pre-train Graph Neural Networks | AAAI 2021 |[repo](https://github.com/rootlu/L2P-GNN) |
| [GPT-GNN: Generative Pre-Training of Graph Neural Networks](https://arxiv.org/abs/2006.15437) | KDD 2020 | 设计了两个预训练任务：attribute generation以及edge generation，且这两个任务迭代进行预测，以此来让GNN既学习到属性信息又学习到结构信息。 |
| [Strategies for Pre-training Graph Neural Networks](https://openreview.net/forum?id=HJlWWJSFDH) | ICLR 2020 | 该文比较面向于生物和化学领域，提出了三个预训练任务：Attribute Masking, Context Prediction以及Supervised Attribute Prediction。其中Supervised Attribute Prediction是在Graph-level上对某一类的结点进行Attribute Prediction，所以通过这样的预训练任务，不仅让模型学习到如何捕获局部信息，还要让其捕获全局信息。 |
| [Deep Graph Infomax](https://arxiv.org/abs/1809.10341) | ICLR 2019 | [TODO] 训练了一个结点编码器，最大化局部结点表示与池化图全局表示之间的互信息 |
| [metapath2vec: Scalable Representation Learning for Heterogeneous Networks](https://dl.acm.org/doi/10.1145/3097983.3098036) | KDD 2017 | [TODO] 基于随机游走 |
| [Network Embedding as Matrix Factorization: Unifying DeepWalk, LINE, PTE, and node2vec](https://arxiv.org/abs/1710.02971) | WSDM 2018 | [TODO] 基于随机游走 |
| [Inductive Representation Learning on Large Graphs](https://arxiv.org/abs/1706.02216) | NIPS 2017 | [TODO] `GraphSAGE` 预测结点的存在性，基于随机游走 | 
| [Variational Graph Auto-Encoders](https://arxiv.org/abs/1611.07308) | NIPS 2016 Workshop | [TODO] 预测结点的存在性（重构图结构） |
| [node2vec: Scalable Feature Learning for Networks](https://arxiv.org/abs/1607.00653) | KDD 2016 | [TODO] 基于随机游走局部信息 |
| [subgraph2vec: Learning Distributed Representations of Rooted Sub-graphs from Large Graphs](https://arxiv.org/abs/1606.08928) | KDD 2016 Workshop | [TODO] 探索了如何将结点表示泛化到不同的任务中 |
| [LINE: Large-scale Information Network Embedding](https://arxiv.org/abs/1503.03578) | WWW 2015 | [TODO] 基于随机游走局部信息 |
| [DeepWalk: online learning of social representations](https://arxiv.org/abs/1403.6652) | KDD 2014 | [TODO] 基于随机游走局部信息 |
| [Heterogeneous Graph Transformer](https://dl.acm.org/doi/10.1145/3366423.3380027) | WWW 2020 | 挺有趣的工作，虽然不属于Pretrained GNN，作者提出了一个在异质图上进行信息传递的注意力机制，使用到了self-attention的思想，分为KVQ矩阵，对于一对结点<s,e,t>s代表源结点，t代表目标结点，e代表边，原始的transformer只有一套KVQ，而本文对于不同类型的结点都有一套不同的KVQ，甚至不同类型的边也会影响到attention的计算。 |



