# HealthSage - Machine Learning Project on Disease Predictions using Symptoms

# Problem Statement

HealthSage is a Python-based application that leverages machine learning to assist users in preliminary disease detection based on their symptoms. Designed with a user-friendly graphical interface powered by Tkinter, HealthSage aims to simplify the often overwhelming process of health information gathering. By utilizing machine learning algorithms such as Decision Tree, Random Forest, Naive Bayes, and k-Nearest Neighbors (kNN), the application provides reliable predictions and serves as an aid for users to understand potential health concerns before consulting a medical professional.

# Why HealthSage?

In today’s world, health information needs are evolving rapidly, influencing how individuals seek medical advice. Many people face challenges when trying to:
  1. Navigate the vast amount of medical information available online.
  2. Understand complex medical terminology.
  3. Make informed decisions about their health.

HealthSage is built to address these challenges by providing an intuitive platform that:
  1. Predicts potential diseases based on symptoms.
  2. Simplifies medical information for better user understanding.
  3. Bridges the gap between users and medical professionals by offering actionable insights.

# Features

1. Symptom-Based Prediction: Users can input up to five symptoms to get predictions.
2. Multiple Machine Learning Algorithms: Supports Decision Tree, Random Forest, Naive Bayes, and kNN for disease prediction.
3. User-Friendly Interface: Built using Tkinter with a clean and intuitive design.
4. Reset and Exit Options: Easy to reset inputs or exit the application.
5. Dynamic Symptom Selection: Dropdown menus allow users to select symptoms from a predefined list.

# Explanation of Files

## training.csv
This is the main dataset which has been used in this project. This dataset consist of mainly two columns "Disease" and "Symptoms" but this dataset is preprocessed so it helps in easily clasifying the data. This dataset is used to train our model.

## testing.csv
 This is the dataset which has been used to test our model so that we can know the accuracy of our model. this dataset is predefined with output.

## Database
The database used in this project is "sqlite" whose name is database.db which consist of four tables in which we have shown the results of four different algorithms.we are saving the results of users with their names for future preferences.

## GUI.py
This is the file which is used to create the interface of our system.GUI stands for Graphical User Interface and to create it we have used Tkinter which gives a software kind of view to our project where user can directly interact with the system by entering the symptoms of dieases and he/she will get the disease through various algorithms.

## Project_ML.ipynb
This is the jupyter notebook which consist of complete code. This is used to explain the working of each and every module used in the project.

## GUI IMG.png
This file contains the screenshot of the built GUI which shows the working of the system

# Working with GUI

## Step 1:
Enter the name in the provided space infront of the label as "Name of the Patient". It is the mandatory field which user have to enter in order to get result.

## Step 2:
Select 5 Symptoms from the dropdown menu which are labelled as Symptom 1, Symptom 2, Symptom 3, Symptom 4, Symptom 5 respectively. If user is not aware of 5 symptoms then it is mandatory for him to enter atleast 2 starting systems, otherwise the result will not come and a message box will pop up for the same

## Step 3:
As per user interest, user can predict the disease using different algorithms such as Decision tree algorithm, Random forest algorithm, Naive bayes algorithm and K-Nearest neighbour. According to algorithm click on buttons:</br>
Press Prediction 1 for Decision tree algorithm</br>
Press Prediction 2 for Random forest algorithm</br>
Press Prediction 3 for Naive bayes algorithm</br>
Press Prediction 4 for K-Nearest neighbour</br>
(User can predict the disease using more than one algorithm at a time)

## Step 4:
Disease Recommendation will be available infront of the labels of algorithm of user's choice.

## Step 5:
Click on "Reset" button to predict the disease for any other patient or Press "Exit System" button to come out of the GUI.
