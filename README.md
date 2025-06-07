# TASK07
 

🎯 Objective:

Use Support Vector Machines for linear and non-linear classification on a binary dataset (indian patient record) dataset).

🛠️ Tools & Libraries Used:

Python

Scikit-learn

NumPy

Matplotlib

Pandas

📁 Project Steps:

1. Load and Prepare Dataset

Used Breast Cancer dataset from Scikit-learn

Selected only 2 features for 2D visualization

Scaled features using StandardScaler

2. Train SVM Models

Trained two models: one with linear kernel and one with rbf kernel

Used SVC from Scikit-learn

3. Visualize Decision Boundaries

Plotted decision surfaces for both models using Matplotlib

Helps visualize how SVM separates the classes

4. Tune Hyperparameters

Tuned C and gamma using GridSearchCV

Improved performance for the RBF model

5. Evaluate Using Cross-Validation

Used cross_val_score for 5-fold validation

Evaluated using accuracy, confusion matrix, and classification report

📊 Dataset:Indian Liver Patient records

Name: 
 Output Highlights:

Decision boundaries for both linear and RBF SVM

Classification metrics: precision, recall, f1-score

Best hyperparameters found using grid search

✅ Outcome:

Successfully built and evaluated SVM classifiers for binary classification with proper tuning and visual interpretation.
