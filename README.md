# churn_data_project

## Bank Customer Churn Prediction
This data science project aims to predict customer churn for a bank using machine learning techniques. By analyzing various customer features, the project develops a predictive model to identify customers who are likely to exit the bank.

## Dataset
The dataset used in this project is Churn_Modelling.csv, which contains customer information such as demographics, account details, and transaction history.

## Project Structure
The project is structured as follows:

- Data exploration and preprocessing
- Feature engineering
- Model selection and hyperparameter tuning
- Model evaluation
- Feature importance analysis
- Handling class imbalance
- Recommendations and insights
- Conclusion and future work

## Models Used
Three classification models were employed in this project:

- Decision Tree
- Random Forest
- Gradient Boosting
Hyperparameter tuning was performed using GridSearchCV to find the best parameters for each model.
Crossfold validation was performed on the Random Forest model to validate the accuracy.

## Results
The Random Forest model with hyperparameter tuning achieved the best performance, with an accuracy of 86%. The model's performance was evaluated using accuracy score, classification report, confusion matrix, and ROC curve.

## Recommendations
Based on the analysis, the project provides actionable recommendations for the bank to reduce customer churn, such as focusing on customer age, number of products, active membership, and geographical location.

## Future Work
Potential areas for future improvement include:

Experimenting with more class weighting techniques
Exploring additional feature engineering techniques
Validating the model's performance on new, unseen data
