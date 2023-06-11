# Deploying Prediction model using Flask Application

Our project extracts the information of videos from the top 25 Youtube channels using YouTube API, including total view count across all 
their videos, comment count, and categories of videos etc. as their variables, and generate a large data frame with over thirty thousand 
observations. By analyzing the data and clean the sample data set, we aim to find variables that can potentially predict with popularity of 
a YouTube video  

After deciding our best performance model, we deploy our final model using Flask, which is a web application framework written in Python. 
We set up a Flask application by creating a Python file and importing the necessary Flask modules. Then we load and preprocess the model by 
loading the trained final model and any required preprocessing steps within the Flask application. Moreover, we define the routes and views 
for the Flask application, specifying the endpoints for accessing the model predictions using the Pickle package in Python. When the general 
outline of the Flask application is built, we implement logic to handle user inputs through HTML forms and pass the input to the model for 
prediction. Additionally, we apply css file for stylistic modification, including font style, color, and margins. 
Finally, we display the model’s prediction results to the users on a web page. 
