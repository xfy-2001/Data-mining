# -
2022春数据挖掘作业整合

这个项目主要是数据挖掘作业的一个整合，存个档。
作业使用python完成，也参考了别人的代码，在别人地代码上进行了一些改动。所使用到的数据集也一并上传了。

作业顺序为：感知机模型、感知机对偶形式、KNN实现、KNN例子2、朴素贝叶斯、朴素贝叶斯实例、决策树模型（实现的是ID3算法）、逻辑斯蒂、一维高斯混合分布、EM混合高斯分布、层次聚类、k均值聚类。

有些地方也是有错误的，我也懒得改了，比如说KNN那个例子交叉验证那一块就写错了，当时还不懂那个包的使用，在后续地代码中就改正过来了可以参考后面的交叉验证板块。朴素贝叶斯模型采用的是最原始的并且是离散的情形，当时老师还讲了LDA模型，但是当时我没太懂就没有实现了。决策树模型也是只做了最简单的，cart算法我也没有实现了，当时老师这个算法讲的比较快，也没太懂，后面复习才懂的，还有后剪枝这个部分不知道怎么实现，别人的代码当时也没有看懂，就只有一个简陋的ID3算法。逻辑斯蒂回归是有坑的，注意sigmod函数，指数溢出报错问题！迭代的步长选取也很单一，是需要改进的。EM算法每一类概率可视化，也是参考了很多代码的，层次聚类画聚类树状图，不会就没有画了。k均值这个地方，初始值选的不好，得到的结果也会非常地差！
