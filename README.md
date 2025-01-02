# Credit Risk Modeling

Problem Description:
- Credit risk refers to the likelihood that a borrower will fail to make payments on their debt obligations, leading to a potential financial loss for the lender. This risk includes delays or defaults on the interest or principal payments.
- The objective of this project is to predict the probability of default for credit card clients. This allows lenders to implement strategies to minimize the risk of financial loss while maintaining the client’s financial health.

Dataset:
Link: https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset 
This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

Data Preprocessing:
Handling Missing Values: Checking and imputing or removing missing data.
Selecting the most relevant features to improve performance.
Scaling Features: Standardizing data to ensure uniform input for models.
Balancing the Data: Addressing class imbalance using SMOTE resampling technique.

Training Models:
Used multiple machine learning algorithms to predict credit risk:
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- Support Vector Classifier (SVC)
Hyperparameter Tuning: Performed grid search for optimal parameters.
Cross-Validation: Evaluated models using cross-validation to ensure generalizability.

Model Evaluation:
Metrics: Accuracy, ROC-AUC score.
Best Model: XGBoost with a ROC-AUC score of 0.76.

Inference:
The credit risk model effectively predicts the likelihood of default, allowing financial institutions to manage and mitigate risks. With proper feature engineering and hyperparameter tuning, XGBoost emerged as the best-performing model in this project.
