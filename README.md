1.	Preprocessing: Encoded and standardized features, used KNN to impute missing data, used SMOTE for data augmentation
2.	Dimensionality Reduction and Clustering: Fitted PCA and UMAP on the data, mitigated overfitting, reduced computation time by 60% ; then fitted K-means++ and DBSCAN on the data to help visualize the global structure of the data distribution
3.	Supervised Learning: Trained Logistic Regression, AdaBoost, Deep Neural Network and XgBoost models on training data by grid search, predicted the state of default in the testing set, achieved 98% maximum accuracy and AUROC of 0.94   
