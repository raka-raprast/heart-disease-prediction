# Heart Disease Prediction
The prospect of using machine learning to predicting a heart disease
## Dataset
Heart Disease UCI : https://www.kaggle.com/ronitf/heart-disease-uci
## Background 
Heart Disease is a sickness that are caused by a lot of factor and it is considered as one of the most deadly sickness in the world. Based on WHO research, it's ranked on the first as "The world’s biggest killer". It is because Ischaemic heart disease, responsible for 16% of the world’s total deaths. Since 2000, the largest increase in deaths has been for this disease, rising by more than 2 million to 8.9 million deaths in 2019. Therefore, prediction for heart disease might be useful for the further research to prevent late treatment for people with symptom of heart disease.
## Goals
*Predicting a heart disease using machine learning

*Choosing the best models to predict heart disease

*Compare effectiveness of Gaussian Naive Bayes, Random Forest and Decision Tree

*Evaluate the model using ROC AUC

## Data Dictionary
*age : age of the patient

*sex : male or female

*cp : chest pain type

*trestbps : resting blood pressure

*chol : serum cholestoral

*fbs : fasting blood sugar

*restecg : resting electrocardiographic

*thalach : maximum heart rate achieved

*exang : exercise induced angina

*oldpeak : ST depression induced by exercise

*slope : the slope of the peak exercise ST

*ca : number of major vessels

*thal : normal/fixed defect/reversable defect

*target : sick or not

## Exploratory Data Analysis
### Distribution of age vs sex with the target class

![download (2)](https://user-images.githubusercontent.com/88265749/127773650-57b23e3e-8d57-4a5a-8b14-31a8fc577ec7.png)

### Variation of age for each target class

![download (1)](https://user-images.githubusercontent.com/88265749/127773829-369b5fda-f78a-4b30-9de1-29442dbf2acd.png)

### Correlation Heatmap

![download](https://user-images.githubusercontent.com/88265749/127773656-a6aa193f-4706-498e-8e4c-3b6f2b5f0537.png)

## Modelling
*The Data splitted into train and test and the train data size used is 30%

*Models that are used for this analysis are Gaussian Naive Bayes, Decision Tree and Random Forest

*Evaluation using Receiver Operating Characteristic - Area Under Curve(ROC AUC)

*Validation using K-Fold Cross Validation

## Evaluation
Evaluation metrics using Receiver Operating Characteristic - Area Under Curve

![Untitled-4](https://user-images.githubusercontent.com/88265749/127774229-0b813b7b-91f2-4f36-9f29-6ccf1e1e1598.jpg)

Based on the evaluation we can conclude that naive bayes has better accuracy than other two models

## Summary

*Machine Learning can be use for predicting heart disease

*Gaussian Naive Bayes are the most effective model in this analysis compared to Random Forrest and Decision Tree

*ROC AUC used for evaluation metrics

*Random Forest and Decision Tree models also give the accuracy above 70%

*Female data is more than male data based on the Variable Distribution graph
