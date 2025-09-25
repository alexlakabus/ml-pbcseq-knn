# PBCSeq KNN Classification

This project demonstrates a **K-Nearest Neighbors (KNN)** clasifier on the **PBCSeq dataset**, handling missing values, scaling numerical features, encoding categorical features, and tuning hyperparameters with **GridSearchCV**.

## Key Features

- Proper handling of missing values
- Categorical feature encoding
- Feature scaling with **StandardScaler**
- 5-fold cross-validation
- Hyperparameter tuning using GridSearchCv

  ## Results

  - Accuracy achieved: ≈0.93
  - Best configuration: Manhattan distance metric, 1 neighbor, distance weight
 
    ## How to run

    1. Clone or download the repo
    2. Open the notebook 'pbcseq__knn.ipnyb' in Jupyter
    3. Run all cells sequetially
   
    ## Key Takeaways

    - Feature scaling is essential for distance-based models like KNN
    - Cross-validation gives a robust estimate of a models performance
    - Proper preprocessing greatly affects model accuracy
