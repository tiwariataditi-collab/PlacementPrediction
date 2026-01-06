# PlacementPrediction
This notebook implements a Placement Prediction model using a custom dataset of student CGPA and IQ. It utilizes Scikit-Learn to build a Logistic Regression classifier. Key steps include data preprocessing, train-test splitting (90/10), and feature scaling. It achieves 90% accuracy and visualizes decision regions for clear insight.
This project implements a machine learning model to predict whether a student will be placed based on their academic and intellectual metrics.

Overview----
The notebook demonstrates a standard end-to-end data science workflow, including data preprocessing, exploratory data analysis (EDA), model training, and evaluation. It uses a dataset containing student records with features such as CGPA and IQ to predict the placement outcome.

Dataset Description---
The dataset consists of 100 student entries with the following columns:

cgpa: Cumulative Grade Point Average of the student.

iq: Intelligence Quotient score.

placement: Target variable (1 for placed, 0 for not placed).

Methodology---
The project follows these key steps:

Data Preprocessing: Removal of unnecessary columns (e.g., 'Unnamed: 0') and handling the data structure.

Exploratory Data Analysis (EDA): Visualizing the distribution of data points using scatter plots.

Feature Selection: Extracting input features (CGPA, IQ) and the target output (Placement).

Data Splitting: Dividing the data into training (90%) and testing (10%) sets using train_test_split.

Feature Scaling: Standardizing the features using StandardScaler to improve model performance.

Model Training: Implementing a Logistic Regression classifier.

Evaluation: Measuring accuracy on the test set and visualizing decision regions.

Results---
Model Accuracy: The Logistic Regression model achieved an accuracy of 90% on the test data.

Visualization: The notebook includes a decision region plot created with mlxtend to show how the model separates placed and non-placed students.

Dependencies--
numpy
pandas
matplotlib
scikit-learn
mlxtend

Would you like me to help you export this model for deployment or perform further analysis on the dataset?
