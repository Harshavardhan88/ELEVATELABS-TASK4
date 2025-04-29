# ELEVATELABS-TASK4

# Classification with Logistic Regression

##  Objective:

Build a binary classifier using Logistic Regression.

##  Dataset:

- **File**: `Housing.csv`
- **Target**: Binary column `is_expensive`, created based on whether `price` is above the median.

##  Tools Used:

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab

##  Workflow Steps:

## 1. Choose a Binary Classification Dataset
- Loaded `Housing.csv`.
- Created a binary target `is_expensive`:
  ```python
  df['is_expensive'] = (df['price'] > df['price'].median()).astype(int)

2. Train/Test Split and Standardize Features
 
 ~Split dataset into train and test sets (80/20).

 ~Scaled numerical features using StandardScaler.

3. Fit a Logistic Regression Model
 
 ~Trained using LogisticRegression() from Scikit-learn.

4. Evaluation

 ~Confusion Matrix

 ~Classification Report

 ~Precision, Recall

 ~ROC-AUC Score

 ~ROC Curve Visualization

5. Threshold Tuning and Sigmoid Explanation

 ~The sigmoid function: ​σ(z)=1/1+e^-z
   maps linear outputs to probabilities.

 ~Used different thresholds (e.g., 0.1 to 0.9) to observe trade-off between precision and recall.

 ~Plotted how precision and recall change with varying thresholds.
