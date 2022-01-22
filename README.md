# Spam-Detection App
This Python WebApp is developed to classify whether the input text provided by the user is a spam or not.

# Dataset and Modelling
The dataset contains of test data which has pre-definedd data of the categories of spam/ham.
Being able to identify spam messages is a binary classification problem as messages are classified as either 'Spam' or 'Not Spam' where previous data are collected which have been categorised as Spam or Ham. Also, this is a supervised learning problem, as we will be feeding a labelled dataset into the model, that it can learn from, to make future predictions.

# Algorithm and processing
The dataset is obtained and undergoes data pre processing techniques.The pre processing techniques consist checking it the data is of text format and we will remove the characters which do not satisfy required patterns. After that we will remove the stopwords and make the data ready for processing. Once the data is pre processed then we apply count vectorizer method which will convert the data  into a matrix format and contain 0s and 1s value signifying the words present or not present in a record. Then we apply the Gaussian Naive Bayes Algorithm which will be used to predict if the text input by the user was spam or not.

# Project Working
This Project is mainly divided into two parts:

Exploring the dataset, Preprocessing texts and traning the model using Sklearn.
Building and hosting a flask web app on Heroku.
About the repository Structure :

Project consists app.py script which is used to run the application and is engine of this app. contians API that gets input from the user and computes a predicted value based on the model.

sms_classifier_model.py contains code to build and train a Machine learning model.
templates folder contains two files main.html and result.html which describe the structure of the app and the way this web application behaves. These files are connected with Python via Flask framework.

static folder contains file style.css which adds some styling and enhance the look of the application.
We are using GaussianNB algorithm to predict the text into spam or not spam and save the model which will be used for classification.
The app can be run on localhost.

![kisspng-flask-python-web-framework-bottle-microframework-django-5b3d0ba62504c0 3512153115307273341516](https://user-images.githubusercontent.com/76935226/140602021-5b17c271-b788-4b43-a018-b84cba1dc617.jpg)
![image](https://user-images.githubusercontent.com/76935226/140602029-62bce97e-5ba9-4087-89fc-7e66f905ec1a.png)
![download](https://user-images.githubusercontent.com/76935226/147869700-17dacd03-d57d-4b53-bdfe-53661aca4cc1.png)


# Working of App

![Screenshot (153)](https://user-images.githubusercontent.com/76935226/140602342-bc88a424-cc7b-4e4b-8376-7c484e7b39ab.png)
![Screenshot (154)](https://user-images.githubusercontent.com/76935226/140602346-69374195-4e7e-4678-91b2-a1edba4a75d3.png)
![Screenshot (155)](https://user-images.githubusercontent.com/76935226/140602349-45836c80-c594-4925-baef-a1a97a51d283.png)
![Screenshot (156)](https://user-images.githubusercontent.com/76935226/140602354-b06e7291-7a7e-4030-8399-b52bd861ddfb.png)



