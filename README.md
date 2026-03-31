# Student Mental Health Prediction Model

## Overview
This Projects predicts the potential CGPA of a student based on their mental abilties, study time and their mental and emotional health and maturity.
This program can help students realise that how and to what consequences their current lifestyle is affecting their current potential.

## Dataset
**File**: https://www.kaggle.com/datasets/sehaj1104/student-mental-health-and-burnout-dataset

**Source**: Kaggle

**Description**: Mental Health and Academic Records of students

**Features Used**: Age, Daily study hours, Daily sleep hours, Screen time hours, Anxiety score, Depression score, Academic pressure score, Financial stress score, Social support score, Physical activity hours, Attendance percentage

**Target**: CGPA

## What the Project does?
This project collects data on the mental well-being and lifestyle of students which it then inturns uses to train itself, so that it can be scaled and trained over large databases, which results in more accurate model, providing better results.

## Working Of the Project
1) To create this machine learning agent, We first select a database which in my case was about the mental health and the grades of students.
2) Then we with the help of python in jupyter notebook import libraries such as pandas to analyse and prepare the data for training the model, and determine the features and target of the model.
3) We use scikit-learn python module, which is a machine learning library and can be used to train models on given datasets.
4) Multiple types of models can be created through with the help of scikit learn, here we have used a Decision Tree Regressor model, which provides us with an accuracy of 79.99% but trains very well, fast and efficient on data.
5) The dataset was also here divided into two parts one for training and one for testing, in a 80-20 split, which is a more genralised split.
6) Then this trained and validated model is used to put new values or inputs and determine and predict a value based on its training on previous data.
7) This is the entire process by which this model works, expalained.

## How to run the program:

### Direct Install
1) Clone or download the repository.
2) Open AQI_Prediction.ipynb in Jupyter Notebook.
3) Run the file

### Command Line
1) Clone Repository
    'git clone <GITHUB_REPO_URL>
     cd <REPO_DIRECTORY>'
2) Install Required Libraries
    'pip install pandas scikit-learn'
3) Temporary convert to python file
   'jupyter nbconvert --to python your_notebook.ipynb'
4) Run the file
   'from python import predict()'

# THANK YOU!
