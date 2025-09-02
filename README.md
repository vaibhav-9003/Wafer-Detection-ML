This project develops a **machine learning pipeline** to predict wafer outcomes (Pass/Fail) in semiconductor manufacturing.  
Since the dataset is highly **imbalanced** (most wafers pass, very few fail), traditional accuracy is misleading.  
Instead, this project optimizes for **recall and F2-score** to ensure defective wafers are detected.
**Problem**: Predict wafer pass/fail outcomes in an imbalanced dataset.

* **Approach**:

  * Feature preprocessing (correlation filtering, scaling).
  * Class balancing using **SMOTE** and **ADASYN**.
  * Model training with **Logistic Regression, XGBoost, Decision Tree**, and a **Dummy baseline**.
  * Hyperparameter tuning using **GridSearchCV**.
  * Threshold tuning to maximize **F2-score**.
