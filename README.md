# Titanic Death Predictor

## Overview
The Titanic Death Predictor is a machine learning project that aims to predict whether a passenger on the Titanic survived or perished. Using historical data from the Titanic disaster, the model uses various features such as passenger age, gender, class, and other factors to make predictions about survival. This project demonstrates the application of machine learning algorithms like Random Forest and Logistic Regression.

## Dataset
The dataset used in this project is from the **Kaggle Titanic dataset**, which contains data about Titanic passengers, including whether they survived or not. The features in the dataset include:
- `PassengerId`: ID of the passenger
- `Pclass`: Passenger class (1, 2, 3)
- `Name`: Name of the passenger
- `Sex`: Gender of the passenger (male, female)
- `Age`: Age of the passenger
- `SibSp`: Number of siblings/spouses aboard the Titanic
- `Parch`: Number of parents/children aboard the Titanic
- `Ticket`: Ticket number
- `Fare`: Amount paid for the ticket
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## Objective
The main objective of this project is to build a machine learning model that can predict whether a given passenger survived the Titanic disaster based on the available features.

## Dependencies
To run this project, the following Python libraries are required:

- `pandas`: Data manipulation and analysis
- `numpy`: Numerical computing
- `scikit-learn`: Machine learning algorithms
- `matplotlib`: Plotting and visualization
- `seaborn`: Statistical data visualization

You can install all the dependencies using `pip` with the following command:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
