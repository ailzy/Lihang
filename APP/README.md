# 附录

这部分大概过一下算法，AB针对无约束最优化问题，C对应约束最优化问题。

## A 梯度下降法
这部分内容是介绍梯度下降, 在NN中用到最多的是SGD, 为什么不介绍SGD?

SGD，S来自与样本的随机。DL中样本很多，通常会分Batch，每个Batch刷的过程就是SGD。实际上数据量小的时候，SGD和GD一样。所以数据的Shuffle就很重要。

## B 牛顿法和拟牛顿法

### BFGS



## C 拉格朗日对偶性

在约束最优化问题中，常常利用拉格朗日对偶性将原问题转化为对偶问题，通过求解对偶问题得到原始问题的解。

为什么要这么做在[CH07](../CH07/README.md)中有说明`这样做的优点，一是对偶问题往往更容易求解；二是自然引入核函数，进而推广到非线性分类问题`

### 原始问题



### 对偶问题



## D 矩阵的基本子空间

向量空间的基的个数即向量空间的维数。

## E KL散度的定义和狄利克雷分布的性质

KL散度是非对称的，也不满足三角不等式，不是严格意义的距离度量。

狄利克雷分布属于指数族分布