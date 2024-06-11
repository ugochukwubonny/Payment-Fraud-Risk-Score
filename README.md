# Payment-Fraud-Risk-Score

## Project Overview
The "Payment Fraud Risk Score" project aims to enhance the security and reliability of payment processing systems by developing a model to predict and score the risk of fraud in payment transactions. By accurately identifying potentially fraudulent transactions, the system can improve its fraud prevention measures and protect users from financial losses.

## Dataset
The dataset used for this project includes various features that characterize payment transactions. These features may include:

Transaction amount
Payment method
Transaction time and date
User account details
Merchant information
Transaction location
Packages Used
The following Python packages were utilized in this project:

warnings: To manage and ignore warnings.
pandas: For data manipulation and analysis.
matplotlib.pyplot: For plotting and visualizing data.
seaborn: For advanced visualizations.
category_encoders.OrdinalEncoder: For encoding categorical features into ordinal format.
sklearn.tree.DecisionTreeClassifier: For implementing the decision tree classifier.
sklearn.tree.plot_tree: For visualizing the decision tree.
sklearn.model_selection.train_test_split: For splitting the dataset into training and testing sets.
sklearn.metrics.accuracy_score: For evaluating the accuracy of the model.
sklearn.pipeline.make_pipeline: For creating a pipeline to streamline data preprocessing and model training.
sklearn.impute.SimpleImputer: For handling missing values.
Model Building
Data Preprocessing
Encoding Categorical Variables: Using OrdinalEncoder to convert categorical variables into a numerical format suitable for model training.
Imputation: Handling missing values using SimpleImputer to ensure a complete dataset for model training.
Model Training
A decision tree classifier was trained to predict the fraud risk score based on the given transaction features.

## Evaluation Metrics
The model was evaluated using the following metrics:

## Accuracy Score
Baseline and Performance
Baseline Accuracy: 0.84
Test Accuracy: 0.87

## Results
The decision tree classifier achieved a test accuracy of 0.87, surpassing the baseline accuracy of 0.84. This indicates that the model is effective in predicting fraudulent transactions based on the given features.

## Conclusion
The model successfully enhances the security and reliability of the payment processing system by providing an accurate risk score for potential fraud. This allows the system to take preventive measures to protect users from fraudulent transactions.
