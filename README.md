# Spam-Detection App
The App is developed to classify whether the input text provided by the user is a spam or not.

# Dataset and Modelling
The dataset contains of test data which has categories of spam/ham.
Being able to identify spam messages is a binary classification problem as messages are classified as either 'Spam' or 'Not Spam' and nothing else. Also, this is a supervised learning problem, as we will be feeding a labelled dataset into the model, that it can learn from, to make future predictions.

This Project is mainly divided into two parts:

Exploring the dataset, Preprocessing texts and traning the model using Sklearn.
Building and hosting a flask web app on Heroku.
About the repository Structure :

Project consist app.py script which is used to run the application and is engine of this app. contians API that gets input from the user and computes a predicted value based on the model.
prediction.py contains code to build and train a Machine learning model.
templates folder contains two files main.html and result.html which describe the structure of the app and the way this web application behaves. These files are connected with Python via Flask framework.
static folder contains file style.css which adds some styling and enhance the look of the application.
We are using GaussianNB algorithm to predict the text into spam or not spam and save the model which will be used for classification.
The app can be run on localhost.
![140600193-88639597-52de-4dce-ba6a-06b80cbe94f2](https://user-images.githubusercontent.com/76935226/140602017-5566fbed-1158-423a-932a-8eac8f9fda19.png)
![kisspng-flask-python-web-framework-bottle-microframework-django-5b3d0ba62504c0 3512153115307273341516](https://user-images.githubusercontent.com/76935226/140602021-5b17c271-b788-4b43-a018-b84cba1dc617.jpg)
![image](https://user-images.githubusercontent.com/76935226/140602029-62bce97e-5ba9-4087-89fc-7e66f905ec1a.png)

