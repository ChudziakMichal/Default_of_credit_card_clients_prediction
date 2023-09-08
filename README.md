# Default_of_credit_card_clients_prediction
Building a model for classification of defaults

Dataset comes from :
https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset

# Steps taken during this project
1) Data description and Exploratory Data Analysis (EDA)
- Checked the basic properties of the data
- Illustrated in graphs the relationships between some of the features and the target variable
2) Feature engineering and feature selection
- Performed standarization and one hot encoding of the features
- Calculated Mutual Information scores to choose variables that will be used in modelling
3) Model Selection and Evaluation
- Choosed final model based on performance of 3 choosed Classifiers 
- Performed parameter tuning using GridSearchCV
- Evaluated final model using classification report
