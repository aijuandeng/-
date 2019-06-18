# 数据挖掘学习小组
## 数据集
data.csv这份数据集是金融数据（非原始数据，已经处理过了）表格中 "status" 是结果标签：0表示未逾期，1表示逾期。

## 目标
对数据进行探索和分析，预测贷款用户是否会逾期

## 要求
数据切分方式 - 三七分，其中测试集30%，训练集70%，随机种子设置为2018

## 任务
**task1**：数据预处理 数据类型的分析 无关特征删除 数据类型转换 缺失值处理 

**task2**：特征挑选 分别用IV值和随机森林等进行特征选择  

**task3**：模型构建 用逻辑回归、svm和决策树；随机森林和XGBoost进行模型构建 评分方式任意，如准确率等。 
模型评估 记录5个模型（逻辑回归、SVM、决策树、随机森林、XGBoost）关于accuracy、precision，recall和F1-score、auc值的评分表格，并画出ROC曲线。 
参数调优 使用网格搜索法对5个模型进行调优（调参时采用五折交叉验证的方式），并进行模型评估，记得展示代码的运行结果。 
模型融合 模型融合，模型融合方式任意，并结合Task5给出你的最优结果。 例如Stacking融合
