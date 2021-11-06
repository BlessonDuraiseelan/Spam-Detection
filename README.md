# Spam-Detection App
The App is developed to classify whether the input text is a spam or not.

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
