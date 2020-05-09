# Disaster_Message_ML_Pipeline
Use a data set provided by Figure Eight containing real tweets/text messages that were sent during disaster events, to repair the data using ETL pipeline and create a machine learning pipeline to build a Supervising Learning Model. The goal is to categorize these events so that the messages can be send to an appropriate disaster relief agency.

## app
Here is the list of html files and Python script to run the web app.
**template**
* master.html  # main page of web app
* go.html  # classification result page of web app

**run.py**  # Flask file that runs app

## data
Build the ETL Pipeline using CSV files contain text messages to process
- disaster_categories.csv  # data to process 
- disaster_messages.csv  # data to process
- process_data.py  # Python script to run ETL pipeline
- DisasterResponse.db   # database to save clean data to

## models
Build a Machine Learning Pipeline
- train_classifier.py
- classifier.pkl  # saved model 
