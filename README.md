### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File description](#file)
4. [Running the web app](#app)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code within the notebooks can be run with the Anaconda distribution of Python. Python 3 was used to do this project.

## Project Motivation<a name="motivation"></a>

This project is part of the Udacity Data Science Nanodegree.


## File description <a name="file"></a>

Data - ETL Pipeline Preparation Notebook: information about implementing ETL pipeline
Models - ML Pipeline Preparation: information about development of machine learning pipeline
App  - run.py: To run the web app. 


## Running the web app <a name="app"></a>

1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/


## Acknowledgements<a name="licensing"></a>

Figure Eight for providing the dataset to classify disaster messages.