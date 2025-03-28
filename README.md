# Titanic_Dataset

# Titanic Survival Prediction Model

## Overview
This project builds a machine learning model to predict whether a passenger survived the Titanic disaster based on various features such as age, gender, ticket class, and fare. The dataset is preprocessed, and a classification model is trained and evaluated.

## Dataset
The dataset used for this project comes from the Titanic dataset available on Kaggle. It includes features such as:
- `Pclass`: Ticket class (1st, 2nd, 3rd)
- `Sex`: Gender of the passenger
- `Age`: Age of the passenger
- `Fare`: Ticket fare
- `Embarked`: Port of embarkation
- `Survived`: Target variable (1 = Survived, 0 = Not Survived)

## Project Workflow
1. **Data Preprocessing**
   - Handling missing values by filling them with median/mode.
   - Dropping unnecessary columns (`Cabin`, `Name`, `Ticket`, `PassengerId`).
   - Encoding categorical variables (`Sex`, `Embarked`).
   - Standardizing numerical features (`Age`, `Fare`).
   
2. **Model Training**
   - Splitting data into training and testing sets (80-20 split).
   - Training a **Random Forest Classifier** to predict survival.
   
3. **Model Evaluation**
   - Measuring performance using **accuracy, precision, recall, and confusion matrix**.
   - Visualizing the confusion matrix to analyze model performance.

## Results
The trained model provides key performance metrics:
- **Accuracy:** Measures overall correctness of predictions.
- **Precision & Recall:** Evaluates false positives/negatives.
- **Confusion Matrix:** Shows detailed classification results.



## Future Improvements
- Experimenting with other models like Logistic Regression, SVM, or XGBoost.
- Hyperparameter tuning for better performance.
- Deploying the model as a web app.




