# 2020-2021-Seminar-Materials
##2020年-2021年讨论班ppt与论文
| Date | Title | Detail | Author | link |
| ------------- |:-------------:| -----:|-----:|-----:|
| 11.27 |SSD: Single Shot MultiBox Detector | 这篇论文提出了单阶段目标检测算法SSD（Single Shot MultiBox Detector），基于将detection转化为regression的思路，可以一次完成目标定位与分类。该算法基于Faster RCNN中的Anchor，提出了相似的Prior box；该算法修改了传统的VGG16网络：将VGG16的FC6和FC7层转化为卷积层，；去掉所有的Dropout层和FC8层；添加了Atrous算法（hole算法），将Pool5从2x2-S2变换到3x3-S1，同时加入基于特征金字塔（Pyramidal Feature Hierarchy）的检测方式，即在不同感受野的feature map上预测目标。 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201127) |
| 11.27 |SSD: Single Shot MultiBox Detector | 这篇论文 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201127) |
| 11.27 |SSD: Single Shot MultiBox Detector | 这篇论文 |Tang JiaWei | [ppt](https://github.com/Tbb-nj/2020-2021-Seminar-Materials/tree/main/20201127) |
