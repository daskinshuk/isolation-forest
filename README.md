# Introduction

In this notebook, credit card dataset has been analyzed, for detecting anomalies, i.e, frauds **Isolation Forest** has been implemented.

# Data Description

Here the Creditcard dataset has been used which is available on **kaggle**, the dataset is having more than 30 attributes,
the target attribute is binary which is having only **1's** and **0's**. The dataset is imbalance, because fraud entries are
rare. 

# Libraries

Python libraries used here are:

* Numpy
* Pandas
* Scikit-Learn
* Matplotlib
* Seaborn

# Project Description

Though the dataset is imbalanced normal classification algorithms won't give good results here, the fraud entries can be treated
as anomalies or outliers, for detecting the anomalies **Isolation Forest** algorithm is implemented.
