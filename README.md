# Sleeping_Disorder_Predicton_Using_ML

**Overview**
This project involves the analysis and classification of sleep and cardiovascular metrics, along with lifestyle factors, for close to 400 fictive persons. The dataset is designed to address the requirements of a health insurance company, aiming to identify whether a potential client is likely to have a sleep disorder. The company intends to use this information to determine the premium for the client.

**Objective**
The primary objective of this project is to automatically identify potential sleep disorders using machine learning classification techniques.

**Problem Solution**
To achieve the project's goal, a classifier will be constructed to predict the presence of a sleep disorder based on various columns in the dataset.

**Dataset Source**
The dataset was sourced from [Kaggle] https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/

**Project Structure**
data.csv.zip: The main dataset file.
sleep_disorder_pred.ipynb: Jupyter Notebook containing the data analysis code.

**Dataset Information**
The dataset contains the following columns:
Person ID
Gender
Age
Occupation
Sleep Duration: Average number of hours of sleep per day
Quality of Sleep: Subjective rating on a 1-10 scale
Physical Activity Level: Average number of minutes of daily physical activity
Stress Level: Subjective rating on a 1-10 scale
BMI Category
Blood Pressure: Indicated as systolic pressure over diastolic pressure
Heart Rate: In beats per minute
Daily Steps
Sleep Disorder: One of None, Insomnia, or Sleep Apnea

**Project Workflow**
**Data Understanding:**
Load the data and check the first few rows.
Examine data types and identify missing values.

**Exploratory Data Analysis (EDA):**
Visualize relationships between variables.
Identify patterns and correlations.

**Data Preprocessing:**
Encode categorical variables.
Explore and transform features as needed.

**Model Development:**
Split the data into training and testing sets.
Experiment with different classification algorithms (Logistic regression, Ridge, SVM, Random Forest Classifier) with cross-validation

**Model Evaluation:**
Evaluate the models' performances (Cross-Validation F1_weighted and classification report).
Fine-tuning.

Feel free to explore, learn, and contribute to the sleep disorder classification project!
