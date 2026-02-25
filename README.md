Fraud Detection Using Machine Learning

This project presents an analysis of supervised and unsupervised machine learning algorithms for detecting fraudulent financial transactions. The dataset contains anonymized credit card transactions with severe class imbalance, where fraudulent cases represent a very small portion of the data.

The workflow includes data preprocessing, correlation analysis, dimensionality reduction using Principal Component Analysis (PCA), clustering methods (KMeans, Agglomerative Clustering, DBSCAN, and Gaussian Mixture Model), linear regression for transaction amount prediction, and logistic regression for fraud classification.

PCA analysis shows that 23 components preserve 90% of total variance, while 25 components preserve 95%, indicating a high-dimensional and complex data structure.

Clustering results suggest that density-based approaches such as DBSCAN are more suitable for modeling fraud as an anomaly detection problem rather than classical segmentation. Logistic Regression achieved strong classification performance (ROC-AUC = 0.881), while Precision-Recall analysis highlighted the challenges caused by class imbalance. Linear regression demonstrated the existence of behavioral patterns in transaction amounts.
