# Table of Contents
1. Installation
2. Project Motivation
3. Fle Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements

# Installation
Libraries required for this project can be found in `requirements.txt`

# Project Motivation
This is the second project of Udacity Data Scientist Nano Degree program, aiming to practice our skills on using Scikit-learn's `Pipeline`. 
Pipeline is a productivity tool that collapses all preprocessing and modeling steps into a one function call. Besides, we practice other
skills like ETL, and web development, which are also important for data scientist.

# File Descriptions
- app
  - templates
    - master.html: this is the main page of the application
    - go.html: this displays the classification result
  - run.py: this is the python file that runs the application
  - mainpage.png: this is the snapshot of main page of the application
  - resultpage.png: this is the snapshot of result page of the application
- data
  - categories.csv: this contains all the categories of the messages
  - messages.csv: this contains all the messages content
  - DisasterResponse.db: this is the sqlite db file that contains cleaned data
  - process_data.py: this is the python file that does the etl
  - ETL Pipeline Preparation.ipynb
- models
  - train_classifier.py: this is the python file that trains the classifier
  - model.pkl: this is the final model
  - ML Ppeline Preparation.ipynb

# Results
Below is a snapshot of the main page
![mainpage](https://github.com/anqi-guo/udacity-dsnd-project2/blob/main/app/mainpage.png)
Below is a snapshot of the classification result page
![resultpage](https://github.com/anqi-guo/udacity-dsnd-project2/blob/main/app/resultpage.png)

# Licensing, Authors, and Acknowledgements
The data was provided by [Appen](https://appen.com/)
