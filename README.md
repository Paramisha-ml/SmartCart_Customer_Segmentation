# SmartCart_Customer_Segmentation

**TYPE** : MINOR PROJECT

**DOMAIN** : Machine Learning

**ALGORITHM** : Agglomerative Clustering

##

This project is a **Customer Segmentation System** built using **Python** and **Scikit-learn**. It analyzes customer demographic, purchasing, and behavioral data to identify distinct customer groups based on their characteristics and shopping patterns.

The dataset contains **2,240 customer records with 22 features**. The data was preprocessed by handling missing values, performing feature engineering, removing selected irrelevant and redundant columns, detecting outliers, encoding categorical features using **One-Hot Encoding**, and applying **Standard Scaling**.

Several meaningful features were engineered, including **Age, Customer Tenure Days, Total Spending, Total Children, and Living With**. Exploratory Data Analysis was also performed to understand relationships and correlations among customer attributes.

For dimensionality reduction and visualization, **Principal Component Analysis (PCA)** was applied to transform the scaled data into three principal components. The first three components explained approximately **44.95% of the variance** in the dataset.

For customer segmentation, **K-Means Clustering** was initially explored using the **Elbow Method** and **Silhouette Score** to determine the appropriate number of clusters. The analysis indicated **4 clusters** as a suitable choice.

The clustering results were further compared with **Agglomerative Clustering**. Based on the observed cluster separation, **Agglomerative Clustering with 4 clusters** was selected for further analysis.

The final segmentation identified four distinct customer groups based on factors such as income, purchasing behavior, total spending, website visits, number of children, education, and living situation.

The clusters revealed meaningful customer segments, including **premium customers** characterized by higher income and spending, as well as **normal customers** with comparatively lower income and spending. One of the identified clusters also showed a relatively higher response rate to campaigns.

<img width="637" height="523" alt="Screenshot (93)" src="https://github.com/user-attachments/assets/91734bb4-fdbe-4672-bb59-9168903f1be4" />

Through this project, I gained practical experience with **data preprocessing, feature engineering, exploratory data analysis, categorical encoding, feature scaling, dimensionality reduction, PCA, K-Means clustering, Agglomerative Clustering, cluster evaluation, and customer segmentation using machine learning**.
