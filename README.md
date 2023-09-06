# Breast-Cancer-Prediction---SVM-Classification
We will predict the breast cancer as malignant or benigh.   
The dataset is downoloaded from Kaggle in the link :  
https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset?select=breast-cancer.csv  
We compare some classification models :  
-Linear SVC
-SVM with SVC using the default kernel RBF
-Randomized search SVM
Then, we visualize the data with the most important features that impact 80% of the variance after applying PCA model.
Even though the dataset contains 31 features, we used only 10 of them that are realted to the mean data (columns suffixed the '_mean').
