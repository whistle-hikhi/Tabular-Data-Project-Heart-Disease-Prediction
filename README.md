# Tabular-Data-Project-Heart-Disease-Prediction

You could visit kaggle link to see the code and dataset: (https://www.kaggle.com/code/hngnguynhuy/tabular-data-project-heart-disease-prediction)
# Table of contents
- [Table of contents](#table-of-contents)
- [Dataset and Objectives](#dataset-and-objectives)
- [Results](#results)

# Dataset and Objectives
In this project, we will apply basic machine learning methods to predict whether a whether people are likely to have heart disease or not based on the Cleveland Heart Disease dataset from UCI Machine Learning Repository . The Cleveland data set includes 14 pieces of information as follows: age, gender, chest pain type, resting blood pressure, serum cholesterol concentration (Serum Cholestrol), fast blood sugar index (Fasting Blood Sugar), resting ECG results (Resting ECG), maximum heart rate (Max heart rate achieved), whether you have angina when exercising or not (Exercise induced angina), ST index at exercise compared to relaxation (ST depression induced by exercise relative to res), ST index in during strenuous activity (Peak exercise ST segment), Number of main vessels (including arteries, capillaries and veins) are illuminated via fluoroscopy (Number of major vessels (0–3) colored by flourosopy), congenital hemolytic anemia (displays the thalassemia), and information about heart disease or not (Diagnosis of heart disease, 0 represents the patient does not have the disease, and 1,2,3,4 represents sick patient). The Cleveland data set includes 303 samples with the above 14 information.

In this project we will use different machine learning algorithms to predict patient views possible heart disease or not. To complete this project, master and know how to use the sklearn library to implement common machine learning algorithms.

For classification problems such as: naive bayes, k nearest neigbors (KNN), decision tree, random forest, Adaboost, gradient boost, XGBoost and support vector machine (SVM). As Understand the machine learning model that integrates ensmple according to bagging, boosting and stacking.

# Results

| Name              | Accuracy (train)  | Accuracy (test)                                                                              
|-------------------|-------------------|----------------                                      
| KNN               |       0.76        |      0.69
| SVM               |       0.66        |      0.67
| Naive Bayes       |       0.85        |      0.84
| Decision Tree     |       1.0         |      0.74
| Random Forest     |       0.99        |      0.87
| Adaboost          |       0.91        |      0.84
| Gradient Adaboost |       1.0         |      0.85
| XGBoost           |       1.0         |      0.84
| Stacking          |       0.95        |      0.92

