# Lasso and Extended Model
## 1 Lasso基础理论

对常用的Lasso及其扩展模型的提出背景、计算方式和优缺点进行简要介绍。

详见 Lasso基础理论.md

- 1 经典Lasso
- 1.1 约束优化角度看Lasso
- 1.2 Lasso的估计及局限
- 2 Adaptive Lasso
- 3 惩罚函数特征
- 4 SCAD
- 5 Elastic Net
- 6 Group Lasso

## 2 项目实践

本项目采用Kaggle上的共享单车使用量数据集(https://www.kaggle.com/c/bike-sharing-demand/data ), 旨在预测美国华盛顿共享单车租赁的使用量。

主要利用python中sklearn库，使用线性回归、Ridge回归、Lasso回归、Elastic Net以及Adaptive Lasso模型对数据进行拟合，进而比较模型的RMSE和score值。

同时，本项目的相关代码也发布在Kaggle上( https://www.kaggle.com/myzhai/bike-sharing-lasso-ridge-elasticnet-adaptivelasso )。 

- 1 描述性统计

- 2 数据预处理

- 2.1 重复值

- 2.2 异常值

- 2.3 特征提取

- 3 特征分析

- 3.1 日期和总租赁数量

- 3.2 月份和总租赁数量

- 3.3 季节和总租赁数量

- 3.4 星期几和总租赁数量

- 3.5 节假日、工作日和总租赁数量

- 3.6 小时和总租赁数量

- 3.7 天气和总租赁数量

- 3.7其他变量和总租赁数量

- 3.8 相关矩阵

- 4 回归模型

- 4.1 线性回归

- 4.2 Ridge回归

- 4.3 Lasso回归

- 4.4 Elastic Net

- 4.5 Adaptive Lasso

- 5 模型比较
  

  