# 2020-2021-Seminar-Materials
##2020年-2021年讨论班ppt与论文
| Date | Title | Detail | Author | link |
| ------------- |:-------------:| -----|-----:|-----:|
| 11.27 |SSD: Single Shot MultiBox Detector | 这篇论文提出了单阶段目标检测算法SSD（Single Shot MultiBox Detector），基于将detection转化为regression的思路，可以一次完成目标定位与分类。该算法修改了传统的VGG16网络：将VGG16的FC6和FC7层转化为卷积层；去掉所有的Dropout层和FC8层；添加了Atrous算法，将Pool5从2x2-S2变换到3x3-S1，同时加入基于特征金字塔的检测方式，即在不同感受野的feature map上预测目标。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201127) |
| 10.23 |Mask Scoring R-CNN | 这篇论文是在Mask R-CNN的基础上提出了一种给算法的“实例分割假设”打分的方法，来提高实例分割模型的性能。而通过实验证明在COCO数据集上的表现结果超越了Mask R-CNN。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201023) |
| 10.13 |Mask R-CNN | 这篇论文提出了Mask RCNN算法，这是一个通用实例分割算法，可以用于做“目标检测”、“目标实例分割”、“目标关键点检测”等多种任务，相比于之前的算法，Mask RCNN都取得了不错的成绩。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201013) |
