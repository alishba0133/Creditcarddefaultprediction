# Credit Card Default Prediction
Performance evaluation of various machine learning classification algorithms to predict credit card defaulters.


#  Dataset Source
Data has been collected from Kaggle and the records are from a bank/credit card issuer without sensitive personal information. The dataset contains the demographic information (like age, gender, marriage, and income) of their customers and the records of their previous history of loan payments and defaults.


#  Project Overview
This project aims to address the imbalance data problem by comparing and analyzing 17 different machine learning classification algorithms to find the optimal model for accurately detecting whether a loan application should be approved.
We aim to identify an optimal model that minimizes bias and accurately predicts the minority class. The evaluation of model performance will primarily focus on the Equal Error Rate (EER), calculated by dividing the total number of incorrect predictions by the dataset's overall size. Given the inadequacy of accuracy for imbalanced datasets due to bias, we will steer clear of using it to compare models. Instead, we will employ alternative evaluation metrics such as EER, ROC-AUC, recall, and F1-Score to gauge the model's effectiveness in precisely predicting the desired outcomes.

Machine Learning Models Used:
1.  Decision Trees
2.  Random Forest
3.  Light Gradient Boosting Machine
5.  Linear Discriminant Analysis
6.  Ridge Classifier
7.  Logistic Regression
8.  CatBoost
9.  AdaBoost
10. Extreme Gradient Boosting
11. K-Nearest Neighbors
12. SVM - Linear Kernel
13. Quadratic Discriminant Analysis
14. Extra Trees
15. Gradient Boosting
16. Naïve Bayes
17. Balanced Random Forest
18. Cost Sensitive Learning (Random Forest).

Data Sampling Techniques Used:
1. SMOTE
2. SVM-SMOTE
3. BORDERLINE SVM-SMOTE
4. SMOTE TOMEK
5. ADASYN
6. Random Oversampling
7. Random Undersampling

#  Model Results

<img width="451" alt="image" src="https://github.com/alishba0133/Creditcarddefaultprediction/assets/40602824/3eeab4cb-06c9-488c-a46a-f9cedccb66b8">

<img width="291" alt="image" src="https://github.com/alishba0133/Creditcarddefaultprediction/assets/40602824/ff01f89d-f14f-49d7-987e-fcaadfe47c39">

After evaluating multiple models and applying multiple sampling techniques and hyperparameter tuning Balanced Random Forest with its default parameters stands out with its well-rounded performance giving us the highest recall value of 0.69 and the highest number of True Positives (TP) of 268 making it the optimal choice for identifying the default cases. The accuracy is 77% the F1-score is 0.52 and we have the lowest EER score of 0.33 suggesting a good class balance indicating giving us an overall high classification accuracy.

#  Conclusion

1. To find the optimal model to predict loan defaulters we built seventeen machine learning classification models Decision Trees, Random Forest, Light Gradient Boosting Machine, Linear Discriminant Analysis, Ridge Classifier, Logistic Regression, CatBoost, AdaBoost, Extreme Gradient Boosting, K-Nearest Neighbors, SVM with a Linear Kernel, Quadratic Discriminant Analysis, Extra Trees, Gradient Boosting, Naïve Bayes, Balanced Random Forest and Cost Sensitive Learning (Random Forest).
2. To tackle the imbalance data problem we used different variations of datasets using seven different data sampling techniques namely SMOTE, SVM SMOTE, BORDERLINE SVM SMOTE, SMOTE TOMEK, ADASYN, Random Undersampling, and Random Oversampling.
3. Balanced Random Forest with imbalanced data and default parameters stands out with its well-rounded performance with an accuracy of 77% and lowest EER score of 0.33.


#  Limitations

1. We did not investigate any feature selection methods.
2. We could not conduct a more extensive search for optimal hyperparameters for the selected models.
3. We did not incorporate deep learning algorithms.



