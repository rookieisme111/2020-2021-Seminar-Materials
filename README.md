# 2020-2021-Seminar-Materials
##2020年-2021年讨论班ppt与论文
| Date | Title | Detail | Author | link |
| ------------- |:-------------:| -----|-----:|-----:|
| 11.27 |SSD: Single Shot MultiBox Detector | 这篇论文提出了单阶段目标检测算法SSD（Single Shot MultiBox Detector），基于将detection转化为regression的思路，可以一次完成目标定位与分类。该算法修改了传统的VGG16网络：将VGG16的FC6和FC7层转化为卷积层；去掉所有的Dropout层和FC8层；添加了Atrous算法，将Pool5从2x2-S2变换到3x3-S1，同时加入基于特征金字塔的检测方式，即在不同感受野的feature map上预测目标。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201127) |
| 10.23 |Mask Scoring R-CNN | 这篇论文是在Mask R-CNN的基础上提出了一种给算法的“实例分割假设”打分的方法，来提高实例分割模型的性能。而通过实验证明在COCO数据集上的表现结果超越了Mask R-CNN。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201023) |
| 10.13 |Mask R-CNN | 这篇论文提出了Mask RCNN算法，这是一个通用实例分割算法，可以用于做“目标检测”、“目标实例分割”、“目标关键点检测”等多种任务，相比于之前的算法，Mask RCNN都取得了不错的成绩。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201013) |
| 7.13 |Modeling Relational Data with Graph Convolutional Networks | 这篇论文引入了图卷积网络(GCN)，并在此基础上提出了关系图卷积网络(R-GCNs)。然后将R-GCN应用于两个基于标准知识库完成的任务：链接预测（用于预测新事实，即挖掘知识库中已存在的实体间未有的关系）和实体分类（对知识库中实体进行分类，即恢复实体的属性），并通过实验验证了R-GCN模型的优越性。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200713) |
| 6.6 |Reasoning With Neural Tensor Networks for Knowledge Base Completion | 这篇论文提出了一个新的神经网络neural tensor network（NTN），它综合了几个以前的神经网络模型并提出一个强于标准神经网络层的更有力去模型化信息之间的关系的方法；提供了一个全新的方式去展现知识库里的实体，之前的论文中只是把实体表现成一个变量，然而如果实体的名称有相同的子串则不能分享统计上的相似属性。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200606) |
| 4.24 |知识图谱研究进展/知识图谱构建技术综述 | 这两篇论文主要是介绍了知识图谱领域相关发展方向和相关技术的进展。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20200424) |
