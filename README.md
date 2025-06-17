# Logistic-Regression-Breast-Cancer

🎯 Objective:

-> Build a binary classifier using logistic regression to predict class labels (e.g., benign vs malignant tumors).

🛠 Tools Used:

 1. Scikit-learn – for model training, evaluation, and preprocessing

 2. Pandas – for data loading and manipulation

 3. Matplotlib / Seaborn – for data visualization and plotting

📋 Steps Followed:

1. Choose a Dataset

-> Used a binary classification dataset such as the Breast Cancer Wisconsin Dataset.

2. Data Preprocessing

-> Split into train/test sets using train_test_split.

-> Standardize features using StandardScaler to improve model convergence.

4. Model Training

-> Fit a logistic regression model using LogisticRegression() from scikit-learn.

5. Model Evaluation

 a. Used evaluation metrics:

  -> Confusion Matrix

  -> Precision & Recall

  -> F1-Score

  -> ROC-AUC Curve

  -> Threshold Tuning

  -> Explored changing the classification threshold instead of using the default 0.5.

  -> Explained the sigmoid function, which maps predictions to a probability between 0 and 1.

OUTPUT:

![Image](https://github.com/user-attachments/assets/5396bc5b-4794-4dc3-8efd-bd55f6bb20e0)
