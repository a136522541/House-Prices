# House-Prices

本项目来源于kaggle新人赛https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview。 利用房屋的各种信息来预测其销售价格。

部分代码参考https://www.kaggle.com/serigne/stacked-regressions-top-4-on-leaderboard/notebook

代码和方法也在csdn上同步，可以参考https://blog.csdn.net/a136522541/article/details/97915847

主要是通过各种方法填充空值、去除无效数据后进行可视化处理，发现一些分布比较偏度过大后，进行正态化处理。最后对非数值类型进行one-hot编码后利用Lasso,XGBoost,GBDT等模型进行预测，最后将各种模型进行stacking获得最优结果。最终成绩为约600名

代码详情可以参考ipynb文件
