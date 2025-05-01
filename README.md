	Preprocessing: Encoded and standardized features, used KNN to impute missing data, used SMOTE for data augmentation
	Dimensionality Reduction and Clustering: Fitted T-SNE and UMAP on the data, mitigated overfitting, reduced computation time by 60% ; then fitted K-means++ and DBSCAN on the data to help visualize the global structure of the data distribution
	Supervised Learning: Trained Random Forest, AdaBoost, Deep Neural Network and CatBoost models on training data by grid search, predicted the state of bankruptcy in the testing set, achieved 98% maximum accuracy of and AUROC of 0.94   
