# Titanic Survival Prediction

This repository implements machine learning models to predict whether a passenger survived or not on the Titanic disaster. The project uses various algorithms to analyze and classify the data from the Titanic dataset.

## Dataset

The Titanic dataset is a well-known dataset used in various data science challenges. It contains information about passengers on the Titanic, including:
- `Survived`: Whether the passenger survived (1) or not (0).
- `Pclass`: The passenger's class (1, 2, or 3).
- `Name`: The passenger's name.
- `Sex`: The passenger's sex.
- `Age`: The passenger's age.
- `SibSp`: Number of siblings/spouses aboard.
- `Parch`: Number of parents/children aboard.
- `Fare`: The fare the passenger paid for the ticket.
- `Embarked`: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Methods Used

- **Data Preprocessing**: Data cleaning and transformation steps, including handling missing values and encoding categorical variables.
- **Exploratory Data Analysis (EDA)**: Understanding patterns and relationships in the data.
- **Modeling**: Various machine learning algorithms including:
  - Logistic Regression
  - Decision Trees
  - Random Forests
  - Support Vector Machines (SVM)
  - K-Nearest Neighbors (KNN)
- **Model Evaluation**: Using metrics like accuracy, precision, recall, and confusion matrices to assess model performance.


## Project Structure

- `data/`: Folder containing the Titanic dataset (`train.csv` and `test.csv`).
- `notebooks/`: Jupyter notebook for loading data, preprocessing, training, and evaluating models.
- `README.md`: Project documentation.
