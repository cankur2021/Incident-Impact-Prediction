 Project Title: Incident Impact Prediction 

🎯 Objective:

The objective is to predict the impact of the incidents/complaints raised by the customers from a service desk platform of an IT company to improve their service. 
A data set which contains the event log of an incident management process extracted from the service desk platform of an IT company was used to carry out this project.
 
📌 Overview: 

✅The project architecture includes the problem identification, data identification, pre-processing, model processing and application. 
✅After acquiring data, the cleaning of data is done i.e. the identification of the missing values and removing the particular columns containing high missing values. 
✅Then by Feature Engineering, the features are extracted. Those features which have high importance were used for Model building. The model which has high accuracy is used for the deployment. 

🛠️ Tools & Techniques:

✅For Exploratory Data Analysis, python libraries were used. 
 ▪️ Numpy & Pandas - for data manipulation
 ▪️ Seaborn & Matplotlib- for data visualization
 ▪️ Sklearn- for model building
 ▪️ Imblearn- for making the data stable
 ▪️ Streamlit & Pickle- for deployment

🔹SMOTE is used for balancing the data. 
 
✅Under Feature engineering, Mutual-info_classif, Extra-tree classifier algorithm shows the features of high importance. 
Similarly, Decision tree classifier shows the features that have high and low importance. Chi-square test is performed for feature selection. 

✅For Model building- Random Forest Classifier, Decision Tree Classifier, Multilayer Perceptron, XGBoost Classifier have been used.

🔍 Insights & Findings:

✅It is observed that the Random Forest Classifier gives the highest accuracy (97.84%), and thus it is considered for the deployment. 
✅Deployment is performed using Streamlit as it can quickly build and deploy powerful data apps.

Thus, developed the model to predict an impact on the basis of an event log of an incident management process extracted from a service desk platform of an IT Company.
