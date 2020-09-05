## Diabetes Prediction using Machine Learning.


### Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Demo](#demo)
  * [Learning Objective](#Learning-Objective)
  * [Technical Aspect](#technical-aspect)
  * [Technologies Used](#technologies-used)
  * [Installation](#installation)
  * [Run](#run)


### Overview 
In this project, the objective is to predict whether the person has Diabetes or not based on various features like Number of Pregnancies, Insulin Level, Age, BMI.The data set that has used in this project has taken from the [kaggle](https://www.kaggle.com/) . "This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage." and used a simple [XGBoost](https://en.wikipedia.org/wiki/XGBoost). 

[<img target="_blank" src="https://github.com/mohithxoxo/Diabetes-Prediction_End-to-End-deployment/blob/master/readme_images/demo.PNG">]


### Motivation
The motivation was to experiment  with end to end machine learning project and get some idea about deployment platform like [Heroku]() and offcourse this "
Diabetes is an increasingly growing health issue due to our inactive lifestyle. If it is detected in time then through proper medical treatment, adverse effects can be prevented. To help in early detection, technology can be used very reliably and efficiently. Using machine learning we have built a predictive model that can predict whether the patient is diabetes positive or not." 

### Demo
[Visit this link for live demo](https://diabetes-prediction-xo.herokuapp.com/)

### Learning Objective
The following points were the objective of the project (The main intention was to create an end-to-end ML project.)  
- Data gathering 
- Descriptive Analysis 
- Data Visualizations 
- Data Preprocessing 
- Data Modelling 
- Model Evaluation 
- Model Deployment 

### Technical Aspect 

- Training a machine learning model using scikit-learn. 
- Building and hosting a Flask web app on Heroku. 
- A user has to put details like Number of Pregnancies, Insulin Level, Age, BMI etc . 
- Once it get all the fields information , the prediction is displyed on a new page . 
### Technologies Used  
![](https://forthebadge.com/images/badges/made-with-python.svg) 

[<img target="_blank" src="https://github.com/scikit-learn/scikit-learn/blob/master/doc/logos/scikit-learn-logo-small.png">](https://github.com/scikit-learn/)
<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>
<img target="_blank" src="https://raw.githubusercontent.com/mohithxoxo/Diabetes-Prediction_End-to-End-deployment/master/readme_images/heroku.jpg" width=170>
<img target="_blank" src="https://raw.githubusercontent.com/mohithxoxo/Diabetes-Prediction_End-to-End-deployment/master/readme_images/numpy.png" width=170>
<img target="_blank" src="https://raw.githubusercontent.com/mohithxoxo/Diabetes-Prediction_End-to-End-deployment/master/readme_images/pandas.PNG" width=170>


### Installation 
- Clone this repository and unzip it.
- After downloading, cd into the flask directory.
- Begin a new virtual environment with Python 3 and activate it.
- Install the required packages using pip install -r requirements.txt

### RUN
- Execute the command: python app.py


