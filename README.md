# Alzheimer's Disease Prediction

## Description 
This project focuses on predicting the likelihood of Alzheimer's disease using a binary classification approach. 
Built with Python, the model employs various data science principles such as data cleaning and standardization. The dataset contained 31 independent variables therefore, 
dimensionality reduction was used through Principal Component Analysis (PCA) to reduce the dataset’s complexity and improve computational efficiency while preserving key features. 
The dataset was balanced through random under-sampling, creating 100 samples for each label. 

Three classifiers were trained: Logistic Regression, K-Nearest Neighbors (KNN), and Support Vector Classifier (SVC), with hyperparameters optimized using Grid Search CV. 
The ROC curve showed that Logistic Regression performed the best, achieving an accuracy of 97%.

## Rationale 
With Alzheimer's disease being a major health concern, early detection through machine learning can assist in providing timely intervention. 
This model offers a data-driven solution for identifying patients at risk, helping medical professionals make more informed decisions about early treatment and prevention.

## Tech Stack 
- **Programming Language**: Python
- **Libraries**:
  - Pandas
  - Scikit-Learn
  - Seaborn/Matplotlib
  - PCA
- **Algorithms**:
  - Logistic Regression
  - K-Nearest Neighbours
  - Support Vector Classifier

 ## Relevance for other projects
 The techniques used in this project, such as dimensionality reduction, sampling strategies, and hyperparameter tuning, 
 are applicable to various machine learning projects dealing with large datasets or imbalanced classes. 
 These methods can improve the interpretability and performance of models across domains such as healthcare, finance, and marketing.
    
