# credit_risk_classification_supervise_learning_machine
## Overview of the Analysis

In this section, I'll provide an overview of the analysis conducted for the machine learning models used in this Challenge:

- **Purpose of the Analysis**: The purpose of this analysis is to assess the performance of machine learning models in predicting credit risk for a financial institution. I aim to determine whether the models can effectively differentiate between healthy loans and high-risk loans.

- **Data Description**: The dataset contains financial information related to loans, and the primary task is to predict the credit risk associated with each loan. The key variable I need to predict is the 'loan_status,' which includes two labels: '0' for healthy loans and '1' for high-risk loans. The dataset was initially imbalanced, with more healthy loans than high-risk loans.

- **Machine Learning Process**: The analysis goes through several stages, including data preprocessing, feature selection or engineering, model selection, and model evaluation. I'll compare two machine learning models: one using the original data and another using resampled data to address class imbalance. The primary method employed in this analysis is Logistic Regression.

## Results

Here are the results of the machine learning models, including balanced accuracy, precision, and recall scores:

### Machine Learning Model 1 (Original Data)

- **Balanced Accuracy**: 95%
- **Precision (Label 0 - Healthy Loans)**: 100%
- **Recall (Label 0 - Healthy Loans)**: 100%
- **Precision (Label 1 - High-Risk Loans)**: 86%
- **Recall (Label 1 - High-Risk Loans)**: 91%

### Machine Learning Model 2 (Resampled Data)

- **Balanced Accuracy (Resampled)**: 99%
- **Precision (Label 0 - Healthy Loans, Resampled)**: 100%
- **Recall (Label 0 - Healthy Loans, Resampled)**: 99%
- **Precision (Label 1 - High-Risk Loans, Resampled)**: 85%
- **Recall (Label 1 - High-Risk Loans, Resampled)**: 99%

## Summary

In summary, the results of the machine learning models are as follows:

- **Machine Learning Model 1 (Original Data)**: This model demonstrates an accuracy of 95% and exhibits reasonable precision and recall scores for both healthy and high-risk loans. While it performs adequately, there is room for improvement in addressing class imbalance.

- **Machine Learning Model 2 (Resampled Data)**: The resampled model shows an improved accuracy of 99% and better precision and recall scores for both labels, making it more effective in classifying credit risk. I recommend using the resampled data model for credit risk analysis.

The resampled model outperforms the original data model in terms of balanced accuracy, precision, and recall. The suitability of the model depends on the specific problem I aim to solve. If the emphasis is on correctly classifying high-risk loans, the resampled model is preferred. However, in some scenarios, the original data model may be sufficient, especially if there are constraints on data resampling or if a balance between precision and recall for both labels is essential.

In conclusion, I recommend using the resampled data model for credit risk analysis due to its improved overall performance and ability to address class imbalance effectively.
---