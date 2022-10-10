# Credit_Risk_Analysis

## Purpose
The purpose of this analysis was to determine which technique or machine learning model can best predict credit risk.

## Results

### Naive Oversampling

#### Balanced Accuracy Score
![Naive Oversampling BAS](Resources/naive_oversampling_bas.png)

#### Imbalanced Classification Report 
![Naive Oversampling](Resources/naive_oversampling.png)

- Balanced accuracy score of 63.67%
- 1% precision of determining high risk with 62% sensitivity, F1 of 2%
- 100% precision of determining low risk with 65% sensitivity, F1 of 79%

### SMOTE Oversampling

#### Balanced Accuracy Score
![SMOTE BAS](Resources/smote_bas.png)

#### Imbalanced Classification Report
![SMOTE Oversampling](Resources/smote_oversampling.png)

- Balanced accuracy score of 63.03%
- 1% precision of determining high risk with 62% sensitivity, F1 of 2%
- 100% precision of determining low risk with 64% sensitivity, F1 of 78%

### ClusterCentroid Undersampling

#### Balanced Accuracy Score
![Cluster BAS](Resources/cluster_bas.png)

#### Imbalanced Classification Report
![ClusterCentroid Undersampling](Resources/cluster_undersampling.png)

- Balanced accuracy score of 51.04%
- 1% precision of determining high risk with 59% sensitivity, F1 of 1%
- 100% precision of determining low risk with 43% sensitivity, F1 of 61%

### SMOTEENN (Over and Under) Sampling

#### Balanced Accuracy Score
![Over and Under BAS](Resources/over_under_bas.png)

#### Imbalanced Classification Report
![Over and Under Sampling](Resources/over_under_sampling.png)

- Balanced accuracy score of 62.48%
- 1% precision of determining high risk with 71% sensitivity, F1 of 2%
- 100% precision of determining low risk with 54% sensitivity, F1 of 70%

### BalancedRandomForestClassifier

#### Balanced Accuracy Score
![BRF BAS](Resources/brf_bas.png)

#### Imbalanced Classification Report
![BalancedRandomForestClassifier](Resources/brf_sampling.png)

- Balanced accuracy score of 78.78%
- 4% precision of determining high risk with 67% sensitivity, F1 of 7%
- 100% precision of determining low risk with 91% sensitivity, F1 of 95%

### EasyEnsembleClassifier

#### Balanced Accuracy Score
![EEC BAS](Resources/eec_bas.png)

#### Imbalanced Classification Report
![EasyEnsembleClassifier](Resources/eec_sampling.png)

- Balanced accuracy score of 92.54%
- 7% precision of determining high risk with 91% sensitivity, F1 of 14%
- 100% precision of determining low risk with 94% sensitivity, F1 of 97%


## Summary



