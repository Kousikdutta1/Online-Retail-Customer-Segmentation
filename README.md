# Online-Retail-Customer-Segmentation
![1_iejTpHhx-u_R73XQD0GFkg](https://user-images.githubusercontent.com/106880838/200382198-aa58d5d8-e892-4306-933f-2db07c450882.jpeg)
---
# Problem Description :
The main goal is to identify major customer segments like customers that are most profitable and the ones who churned out using Unsupervised ML Clustering Algorithms to prevent further loss of customer by redefining company policies. In this project, our task is to identify major customer segments on a transnational dataset which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. The dataset provided contains information about Invoice No, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID and Country for each transaction.

---
# **Summary**
## Steps Involved : 
### **Data Preprocessing :**
Started with understanding the dataset, some basic inspection like checking columns, data statistics, missing values, duplicate values after that handling those null values, duplicates and some data cleaning.

### **Feature Engineering :** 
Some new features have been created to get more insights from the datset.

### **Exploratory Data Analysis :** 
we tried to get some insights from the data by plotting graphs and charts. We saw top customers who have purchased the maximum quantity. Interestingly. We saw not only maximum transactions come from the UK but also most customers are located in the United Kingdom.

### **RFM Analysis :**
Next, we formulated some quantitative factors such as Recency, Frequency and Monetary known as RFM model for each of the customers. We did some feature engineering and EDA on this new dataset as well. We also made some transformations in this dataset to make it ready to be passed to different clustering algorithms.

### **Model Summary :**

1. We started with binning of RFM Score and RFM Group segmentation model, then moved to more complex models.

2. We moved to k-means clustering , we selected optimal number of clusters with the help of Elbow Curve and Silhouette Score and visualized the results with different number of clusters. As we know there is no assurance that k-means will lead to the global best solution. We moved forward and tried Hierarchical Clustering and DBSCAN clustering as well.

3. We created several useful clusters of customers on the basis of different metrics and methods to categorize the customers on the basis of their beavioural attributes to define their valuability, loyality, profitability etc. for the business. Though significantly separated clusters are not visible in the plots, but the clusters obtained is fairly valid and useful as per the algorithms and the statistics extracted from the data.
