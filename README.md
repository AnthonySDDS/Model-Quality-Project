Overview
This project aims to predict customer churn using a machine learning approach. After evaluating multiple models and techniques, an optimized Random Forest Classifier was selected for its balanced performance and ability to reduce misclassification errors.

Dataset
The dataset used for training and evaluation includes customer information and churn labels. It was preprocessed to handle missing values, encode categorical variables, and scale numerical features. To address class imbalance, SMOTE (Synthetic Minority Over-sampling Technique) was applied.

Model: Optimized Random Forest
Key Highlights:
Precision: 61%

Recall: 60%

F1-Score: 61%

Evaluation: Macro-averaged

Improvements:
Initially, the model struggled with high false positives and missed churn cases.

SMOTE was used to balance the dataset and give more weight to minority (churn) cases.

Hyperparameter tuning (e.g., n_estimators, max_depth, min_samples_split) significantly improved model performance.

Post-optimization, the model became more selective, improving precision while maintaining strong recall.

Conclusion
The final Random Forest model provides a reliable and balanced method for predicting customer churn. It effectively reduces false predictions and captures a meaningful portion of churners, making it suitable for business applications like customer retention strategies and proactive engagement.