# Credit_Risk
# Credit_Risk_Analysis

## Overview
The purpose of this project is to analyze credit risk data from the company LendingClub, a peer-to-peer lending service. 

## Results
### Oversample Model
- Balanced Accuracy Score is 64.7%.
- Using the Confusion Matrix to calculate the Imbalanced Classification Report, 'high_risk' precision is at 1%, a recall (sensitivity) of 62%, and a F1 score 2%.
-'low_risk' precision is very high at 100%, with a recall (sensitivity) of 67%, and a F1 score of 80%.

### Undersample Model
- Balanced Accuracy Score is 51.77%.
- Using the Confusion Matrix to calculate the Imbalanced Classification Report, the 'high_risk' precision is at 1%, a recall (sensitivity) of 57%, and a F1 score of 1%.
- The'low_risk' precision is very high again at a 100%, with a recall (sensitivity) of 46%, and a F1 score of 63%.

### SMOTE Model
- With the SMOTE model, the Balanced Accuracy Score is 62.5%.
- Using the Confusion Matrix to calculate our Imbalanced Classification Report, the 'high_risk' precision is at 1%, a recall (sensitivity) of 62%, and a F1 score of 2%.
- The 'low_risk' precision is again 100%, with a recall (sensitivity) of 63%, and a F1 score of 77%.

### SMOTEENN Model
- Balanced Accuracy Score is 62.5% (the same as the SMOTE model).
- Using the Confusion Matrix to calculate the Imbalanced Classification Report, 'high_risk' precision is at 1%, with a recall (sensitivity) of 71%, and a F1 score of 2%.
- 'low_risk' precision is again 100%, with a recall (sensitivity) of 54%, and a F1 score of 70%.

### Balanced Random Forest Classifier Model
- Balanced Accuracy Score is 78.78%.
-'high_risk' precision is at 4%, with a recall (sensitivity) of 67%, and a F1 score of 7%.
- 'low_risk' precision is 100%, with a recall (sensitivity) of 91%, and a F1 score of 95%.

### Easy Ensemble Classifier Model
-  Balanced Accuracy Score is at 92.5%.
- Using the Confusion Matrix to calculate the Imbalanced Classification Report, 'high_risk' precision is at 7%, with a recall (sensitivity) of 91%, and a F1 score of 14%.
- 'low_risk' precision is 100%, with a recall (sensitivity) of 94%, and a F1 score of 97%.

## Summary
The Easy Ensemble model is the most accurate with an accuracy score of 92.5%. As an analyst, I would recommend that the Easy Ensemble Classifier model is the way to go for the Lending Club when determining credit risk for their customers.
