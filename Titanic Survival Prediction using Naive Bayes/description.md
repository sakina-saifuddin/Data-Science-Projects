# Titanic Survival Prediction Using Naïve Bayes
This project uses the Titanic dataset to predict whether a passenger survived or not based on personal and travel-related features such as class, age, sex, fare, and embarkation point. A Naïve Bayes classification model is applied to analyze these factors and estimate survival probabilities.
## Dataset Information
The dataset used in this project provides information about the passengers in the titanic It includes the following columns:

| Variable | Description |
| --- | --- |
| PassengerId | A unique identification number assigned to each passenger. |
|Survived | Survival outcome of the passenger (1 = survived, 0 = did not survive). |
|Pclass | Passenger class indicating socio-economic status (1st, 2nd, or 3rd class). |
|Name | Full name of the passenger. |
|Sex | Gender of the passenger (male or female). |
|Age | Age of the passenger in years. |
|SibSp | Number of siblings or spouses traveling with the passenger. |
|Parch | Number of parents or children traveling with the passenger. |
|Ticket |Ticket number assigned to the passenger. |
|Fare | Amount of money paid for the ticket. |
|Cabin | Cabin number where the passenger stayed (if available). |
|Embarked | Port where the passenger boarded the ship (S, C, or Q). |

## Objective
To predict the survival of Titanic passengers using a Naïve Bayes classification model based on their personal, social, and travel-related features.

## Approach
- Data Collection: Load the Titanic dataset containing passenger details (personal, social, and travel-related features).
- Data Cleaning & Preprocessing:
- Handle missing values (e.g., fill missing ages with median, missing embarked points with mode).
- Remove irrelevant columns (e.g., Name, Ticket, Cabin).
- Encode categorical variables like Sex and Embarked into numerical values.
- Feature Selection: Define input features (Pclass, Sex, Age, SibSp, Parch, Fare, Embarked) and target variable (Survived).
- Train-Test Split: Divide the dataset into training and testing sets (e.g., 80% training, 20% testing).
- Model Training: Train a Naïve Bayes classifier (GaussianNB) on the training set.
- Prediction: Use the trained model to predict survival on the test set and on new/random passenger data.
- Evaluation: Assess model performance using accuracy, confusion matrix, and classification report.

## Impact
The project’s impact lies in demonstrating how machine learning can be used to analyze historical data, uncover factors affecting survival, and provide insights for risk assessment and decision-making in safety-critical scenarios.
