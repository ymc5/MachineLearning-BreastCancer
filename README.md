# MachineLearning-BreastCancer
Machine learning prediction model demo conducted on breast cancer dataset

---

## 1. Breast Cancer Diagnosis Machine Learning Classification 

### Steps:

### (1) Download the dataset .

### (2) Read the CSV file using Pandas and divide the dataframe into a feature matrix dataset and outcome variable. 

### (3) Split the dataset into training and test sets.

### (4) Train any two ML classifiers (Logistic Regression, SVM, Random Forest).

### (5) Evaluate the performance of each trained ML model on the test set and print:
- **SVM Classifier Evaluation:**
  - Accuracy: 0.912
  - Recall: 0.836
  - Precision: 0.933
  - Specificity: 0.962
  - F1 Score: 0.882

  Classification Report:
  ```
                precision    recall  f1-score   support

           0       0.90      0.96      0.93       104
           1       0.93      0.84      0.88        67

    accuracy                           0.91       171
   macro avg       0.92      0.90      0.91       171
weighted avg       0.91      0.91      0.91       171
  ```

- **Logistic Regression Evaluation:**
  - Accuracy: 0.936
  - Recall: 0.925
  - Precision: 0.912
  - Specificity: 0.942
  - F1 Score: 0.919

  Classification Report:
  ```
                precision    recall  f1-score   support

           0       0.95      0.94      0.95       104
           1       0.91      0.93      0.92        67

    accuracy                           0.94       171
   macro avg       0.93      0.93      0.93       171
weighted avg       0.94      0.94      0.94       171
  ```

---
