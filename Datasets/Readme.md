# Dataset Information

This project uses the **Breast Cancer Wisconsin Dataset**, which is a built-in dataset provided by the **scikit-learn** library.

## Dataset Source
- Loaded directly using:  
  `sklearn.datasets.load_breast_cancer()`
- No external CSV file is required.

## Description
The dataset is used for binary classification and contains medical diagnostic features computed from breast cancer cell images.

### Target Classes
- **0** → Malignant
- **1** → Benign

### Dataset Size
- Total Samples: 569
- Number of Features: 30 (numerical)
- Target Variable: Binary (0 / 1)

## Why This Dataset?
- Clean and well-structured
- Suitable for classification problems
- Ideal for evaluating models using:
  - K-Fold Cross-Validation
  - Stratified K-Fold Cross-Validation
- Commonly used in academic and research projects

## Usage in This Project
The dataset is used to:
- Train and evaluate a Random Forest classifier
- Perform cross-validation
- Compare Random Forest performance with SVM and Decision Tree models
