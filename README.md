# Text-classification
A work on text classification
#### language：python
#### 数据来源：从THUCNews文本数据集中选取了财经、科技、体育、家居、教育、房产六类，每类5000条数据。
#### 文本分类思路：
1、导入相应的包  
2、加载数据，进行文本预处理（正则匹配，jieba分词，去停用词）  
3、划分数据集（一种是类别均衡划分，一种是类别不均衡划分）（训练集：测试集：验证集=8:1:1）  
4、文本向量化以及特征选择（使用卡方统计量进行特征选择）  
5、使用了朴素贝叶斯、KNN、GBDT三种模型进行了学习，最终报告了混淆矩阵、报告精确度、召回率、F1分数、支持度、宏平均与微平均F1分数等指标评估模型  
最后还加上了不进行特征选择时各个模型的分类结果
