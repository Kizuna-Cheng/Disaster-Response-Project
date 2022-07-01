# Disaster-Response-Project

This project will include a web app where an emergency worker can input a new message and get classification results in several categories. The dataset used for this project contains real messages that were sent during disaster events. In the backend, the goal would be to create a machine learning pipeline to categorize these events so that messages can be sent to an appropriate disaster relief agency.

## Key Libraries and Techniques
pandas, numpy, sqlite3, sqlalchemy, matplotlib, nltk, Sklearn (GridSearchCV, RandomForestClassifier, Pipeline, FeatureUnion, CountVectorizer, TfidfTransformer, train_test_split, classification_report)

## Project Components
There are three components you'll need to complete for this project.

### 1. ETL Pipeline
In a Python script, process_data.py, write a data cleaning pipeline that:

- Loads the messages and categories datasets
- Merges the two datasets
- Cleans the data
- Stores it in a SQLite database
### 2. ML Pipeline
In a Python script, train_classifier.py, write a machine learning pipeline that:

- Loads data from the SQLite database
- Splits the dataset into training and test sets
- Builds a text processing and machine learning pipeline
- Trains and tunes a model using GridSearchCV
- Outputs results on the test set
- Exports the final model as a pickle file
### 3. Flask Web App

- Modify file paths for database and model as needed
- Add data visualizations using Plotly in the web app

![alt text](https://github.com/Kizuna-Cheng/Disaster-Response-Project/blob/main/pictures/Disaster%20Response%20Flask%20App.png)
