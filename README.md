# Classification-of-Apple-Stock-Market-and-Diabetes-Dataset-
Classification of Apple Stock Market and Diabetes Dataset 
This project explores the classification problem of two datasets: the Apple stock market dataset and diabetes dataset. 
With the use of various machine learning models I've predicted the target variables.
I've observed that by using the models, both the datasets performed better with the decision tree model. 
Q learning is also performed in the taxi environment using the OpenAI gym.

## Objective of project :
The Aim of the classification problem is to identify whether the stock revenue of apple is in profit or loss (dataset 1) and if the patient has a diabetic condition (dataset 2). 
The first dataset used in this project is the “Apple revenue from 1980 to 2022” dataset from the Kaggle. 
Here the class label being either Profit or Loss depending on the Values of Open, High , Low, Close and the volume traded in each day from 1980 to 2022. 
The second dataset is the “Diabetes_Classification_dataset “from Kaggle.
The dataset contains 8 independent variables such as Number of times pregnant, Plasma glucose concentration, Diastolic blood pressure, BMI, age etc., and one class variable examining whether the patient contains a diabetes disease or not.

The main objective of this project is to correctly predict the target variables of both the datasets I have used using the machine learning models and check which works the best. 
Both the datasets are evaluated using the Decision tree, SVM, Naive, Q Learning

## Model development
In order to analyze both the selected datasets and predict the targeted variables, I used four different machine learning models on both the datasets: 
SVM, Decision Tree, Naive Bayes, and Q learning. An already in-built library named sk-learn was used in order to train each model. 

## Discussion of the results :
From modeling with different models on two distinct datasets, I can see that Model performance varies from dataset to dataset; however, we can predict which model may be optimal for a particular problem type. Model performance is also dependent on attributes such as dataset size, data noise, linearity of the dataset, and so forth.
The datasets were fairly clean with just some removal of outliers and slight preprocessing and SVM,Naive Bayes and Decision Tree were applied to both datasets which were then modelled.
Q learning was also done to both datasets
