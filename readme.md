# 登革热数据分析

## 一、前言

本次项目主要是服务于学校数据分析课程项目，较为简陋，不想调模型，很麻烦，随便做一下。

项目主要以数据清洗进行特征工程，并从时间序列做基础性预测开始，分别使用XGBoost回归模型、分类（随机森林）模型、聚类（K-means)分析以及时空热点分析进行数据预测分析。

## 二、前期准备工作

### 2.1 版本推荐

我在本次实验使用的是3.10.9版本Python，建议使用相同版本Python以避免库不兼容。

### 2.2 依赖下载

综上模型所述，我们需要下载一些依赖库。

```powershell
pip install pandas numpy matplotlib seaborn scikit-learn xgboost prophet statsmodels folium imbalanced-learn joblib python-dateutil
```

当中可能会因为依赖Stan的prohet库安装失败，你可以尝试以下步骤。

```powershell
pip install cmdstanpy
pip install prophet
```

如果你使用的是Anaconda，我也不知道怎么安装，你需要自己AI查询。