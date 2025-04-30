# ELEVATELABS-TASK4

# Logistic Regression Binary Classifier

This project demonstrates how to build a binary classification model using Logistic Regression on the Breast Cancer Wisconsin dataset.

## Dataset :

    - Source: Provided `data.csv`
    - Target variable: `diagnosis` (Malignant = 1, Benign = 0)
    - Total samples: 569
    - Features: 30 numerical attributes related to tumor characteristics

## Steps Performed:

   1. **Load and explore dataset**
   2. **Data cleaning**: Drop unused columns, encode target
   3. **Train/Test split**
   4. **Feature scaling** using StandardScaler
   5. **Model training** using `LogisticRegression`
   6. **Evaluation**:
         - Confusion Matrix
         - Precision, Recall, ROC-AUC
   7. **ROC curve visualization**
   8. **Threshold tuning**
   9. **Sigmoid function** explanation and visualization


## Requirements:
   
    - `scikit-learn`
    - `pandas`
    - `matplotlib`
    - `seaborn`
