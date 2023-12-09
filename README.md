#Breast Cancer Classification Project

##Overview
This repository contains code for a machine learning project focused on breast cancer classification. The project utilizes supervised machine learning algorithms, specifically Naive Bayes and Decision Tree, to train and test models for the classification of breast cancer 

##Table of Contents
###Introduction
###Dataset
###Algorithms
###Usage
###Limitations

##Introduction
Breast cancer is a significant health concern, and early detection plays a crucial role in improving patient outcomes. This project aims to contribute to the field of medical diagnostics by employing machine learning algorithms to classify breast cancer data by given variables.

##Dataset
The dataset used in this project is sourced from data.https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data. It includes various features related to breast cancer patients, such as radius mean, texture mean, and other relevant medical indicators. The dataset is split into training and testing sets to evaluate the performance of the machine learning algorithms.

##Algorithms
The project focuses on two supervised machine learning algorithms:

###Naive Bayes:
A probabilistic algorithm based on Bayes' theorem, assuming independence between features. It is particularly useful for classification tasks and is known for its simplicity and efficiency.

###Decision Tree:
A tree-like model where decisions are made at each node based on feature values. Decision trees are interpretable and can capture non-linear relationships in the data.

##Usage
To run the project, follow these steps:
Clone/download the repository.
Pull the ipynb into Google Colaboratory
Insert the given dataset into an accessible folder on your Google Drive
Change this given line: "raw_data = pd.read_csv('/content/drive/My Drive/HI1020/breast-cancer.csv')" to refelct the change.

##Limitations
While the project aims to contribute to breast cancer classification, it is essential to acknowledge its limitations:

###Data Quality:
The performance of the models heavily relies on the quality of the input data. Inaccuracies or biases in the dataset can impact the effectiveness of the algorithms.

###Feature Selection:
The choice of features in the dataset may not capture all relevant information for accurate classification. Further feature engineering and selection may be necessary.

###Model Complexity:
The selected algorithms have their own assumptions and limitations. In more complex scenarios, more sophisticated models may be required.

###Interpretability:
While Decision Trees are interpretable, they may not generalize well to all situations. Interpretability should be balanced with the need for model accuracy.


