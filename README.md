Diabetes Prediction Using Machine Learning
Project Overview

This project uses machine learning to predict whether a person is likely to have diabetes based on medical information such as glucose level, blood pressure, BMI, age, and other health-related features.

The project was created as part of my machine learning practice and revision. It helped me understand the complete workflow of building a classification model, from loading the dataset to evaluating the model and making predictions.

Dataset

The dataset contains medical information for multiple patients.

The input features include:

Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age

The target column is:

Outcome = 0 → The person is not diabetic
Outcome = 1 → The person is diabetic
Objective

The objective of this project is to build a machine learning model that can predict whether a person is diabetic based on the available medical features.

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Jupyter Notebook
GitHub
Project Workflow

The project follows these steps:

Import required libraries
Load the diabetes dataset
Explore and understand the data
Check the dataset shape and basic information
Separate features and target labels
Split the data into training and testing sets
Train a machine learning classification model
Evaluate the model using accuracy score
Make predictions using new patient data
Model Used

The machine learning model used in this project is:

Support Vector Machine / Logistic Regression
(Keep only the model you actually used.)
Model Evaluation

The model is evaluated using accuracy score on the training and testing data.

Training accuracy shows how well the model learned from the training dataset.

Testing accuracy shows how well the model performs on new and unseen data.

Project Structure
diabetes_prediction/
│
├── data.ipynb
├── diabetes.csv
└── README.md
How to Run the Project
Clone this repository:
git clone https://github.com/ananthumangalan/Diabetes_prediction_using_ML.git
Open the project folder.
Install the required libraries:
pip install pandas numpy scikit-learn
Open the Jupyter Notebook:
data.ipynb
Run the notebook cells step by step.
What I Learned

Through this project, I revised and practiced:

Loading and exploring a dataset
Understanding input features and target labels
Splitting data into training and testing sets
Training a classification model
Evaluating model performance
Making predictions using new input data
Using Git and GitHub to manage the project
Conclusion

This project helped me strengthen my understanding of the basic machine learning workflow using a healthcare-related classification problem.

It also gave me practical experience in working with medical data and building a prediction model.

Author

Ananthu MS
