# Customer Churn Prediction

This machine learning project predicts whether a customer will churn based on their demographics, contract, and service usage.

## Project Goals

- Build a predictive model using scikit-learn
- Evaluate performance with classification metrics
- Visualize key insights and features

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Result

After analyzing the accuracy, confusion matrix, ROC curve, recall, and standard deviation, we can conclude that XGBOOST is the most performant algorithm in our case. It achieves the highest accuracy (0.78), demonstrates better class separation in the confusion matrix, and has the best AUC score (0.82) on the ROC curve. Additionally, XGBOOST shows a low standard deviation, indicating that its performance is stable and consistent across different runs or data splits. 
 XGBOOST consistently outperforms the other two models across all key evaluation metrics.