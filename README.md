# Diabetes_Prediction

Link for my app: [https://fluffy-big-decision.anvil.app](https://fluffy-big-decision.anvil.app) (For now this app is not full-time hosting)

Diabetes is a medical disorder that impacts how well our body uses food as fuel. Most food we eat daily is converted to sugar, commonly known as glucose, and then discharged into the bloodstream. Our pancreas releases insulin when the blood sugar levels rise.

Diabetes can cause blood sugar levels to rise if it is not continuously and carefully managed, which raises the chance of severe side effects like heart attack and stroke. We, therefore, choose to forecast using Python machine learning.

## Data Description
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes, based on certain diagnostic measurements included in the dataset. The dataset has 789 rows and 9 columns.

## Model used:

In this dataset I've used **Support Vector Machine(SVM)** for prediction.

Support Vector Machine (SVM) is a supervised machine learning algorithm which is mostly used for classification tasks. It is suitable for regression tasks as well.

Supervised learning algorithms try to predict a target (dependent variable) using features (independent variables). Depending on the characteristics of target variable, it can be a classification (discrete target variable) or a regression (continuous target variable) task. Prediction is done with a mapping function which maps independent variables to dependent variable. The mapping function for SVM is a decision boundary which makes the distinction between two or more classes. How to draw or determine the decision boundary is the most critical part in SVM algorithms.

![img](https://miro.medium.com/v2/resize:fit:640/format:webp/1*mRPaFRxCP67yGqhvCMpJvA.png)

## Final Model:

I have created an Anvil Application based on predictive model, where I am taking multiple diagnosis values like blood pressure, BMI, glucose level, etc. and displaying the output predicted by the SVM.
![diapic](https://github.com/neeharika567/Diabetes_Prediction/assets/111648731/0e4df5e2-f3a4-4799-a69b-5b76a594e3ed)



