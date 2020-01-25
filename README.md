README.md - Customer churn prediction using Spark 


## 
**Project Title**

Predicting Customer Churn (Udacity Data Science Course Capstone project). 


## 
**Description**


### **Goal**

The goal of this capstone project is to build a model that predicts customer segments that are likely to churn by utilizing the knowledge and skills learned throughout the Data Science Nanodegree Program. Pyspark was used in Jupyter notebook launched on AWS to take advantage of the fast distributed data processing power of Spark.


### **Overview**

What is customer churn? Simply put, customer churn is a loss of customers. In the world of business, customer churn is a big concern because it is directly related to profitability. When customers discontinue service or chose a competitor, it leads to decreases in revenue. The difficulty is determining the cause of such customer attrition because it is likely to be a combination of multiple factors, not a single cause.

It is a challenging problem to predict who will discontinue their relationship with businesses based on the data collected from customers. As is always the case in any given industry or organization, retaining existing customers can be much harder than acquiring new ones. Thus, predicting churn rates is important so that the loss doesn’t result in a significant decline in revenue or brand image.

In this project, I examined the customer data of Sparkify, an online music app service, and built several models to figure out the factors that influence customer churn rates. The best performing model was chosen and tuned for final selection. The dataset was provided by Udacity as part of the Data Science Nanodegree Capstone project. Below are my research questions.

**Research Questions:**



1. Are there any differences between churned and non-churned customers in their demographic and paid service status?
2. Are there any differences between churned and non-churned customers in their activities on the site?
3. What is the best machine learning model that predicts customer churn for the data?
4. What are the most important feature?

**Dataset used:**

The fictitious Sparkify customer event data provided by Udacity was used (mini dataset). This data included the demographic and activity information of customers on the music app site and can be found here: s3n://udacity-dsnd/sparkify/mini_sparkify_event_data.json

**Analyses used:**

*   Descriptive analyses to compare churned and no-churned customer groups
*   Logistic Regression, Random Forest, and Gradient-Boosted Classifiers trained to predict customer churn rates
 


## 
**Dependencies and Installation**

You need to install the following Spark, Python, and visualization packages and libraries:



*   PySpark: pip install pyspark
*   Scikit-learn: pip install scikit-learn
*   Pandas: pip install pandas
*   matplot: pip install matplotlib
*   seaborn: pip install seaborn


## **Acknowledgments**



*   Udacity course materials
*   Spark tutorials:
    *   [https://spark.apache.org/docs/latest/api/python/index.html](https://spark.apache.org/docs/latest/api/python/index.html)
    *   [https://spark.apache.org/docs/2.1.0/mllib-evaluation-metrics.html](https://spark.apache.org/docs/2.1.0/mllib-evaluation-metrics.html)
*   For plotting metrics:
    *   [https://stackoverflow.com/questions/54425084/pyspark-get-threshold-cuttoff-values-for-each-point-in-roc-curve](https://stackoverflow.com/questions/54425084/pyspark-get-threshold-cuttoff-values-for-each-point-in-roc-curve)
