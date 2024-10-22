# Recommender System推荐系统

这是一个正在开发的基于tensorflow2实现的推荐系统，作者于兰州大学自主学习实现的一些推荐系统算法。

数据集：电影MovieLens-100k, MovieLens-1m, MovieLens-20m，音乐lastfm，书Book-Crossing，以及一些satori知识图谱。

算法：UserCF（基于用户的协同过滤）, ItemCF（基于物品的协同过滤）, LFM, SLIM, GMF, MLP, NeuMF, FM, DeepFM, MKR, RippleNet, KGCN等。

评估指标：点击率预测ctr的auc和f1，topk评估的准确率precision和召回率recall。

## 需求

* Python 3.11
* Tensorflow 2.5.0

## 运行

在PyCharm里面将此文件的父文件夹作为项目打开，设置好Python3.11的环境并使用pip安装tensorflow的2.5.0版本。

到Recommender_System/algorithm/xxx/main.py源码文件下并点击运行。

MovieLens-20m数据集太大了因此不被包含在此项目文件中，如果你需要这个数据集，[下载MovieLens-20m](http://files.grouplens.org/datasets/movielens/ml-20m.zip)并将'ml-20m'文件夹放到'Recommender_System/data/ds'目录下。
