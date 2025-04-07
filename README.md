## 🏦 Loan Risk Prediction

This project uses a structured machine learning approach to predict loan default risk using historical financial and behavioral data. The analysis follows the CRISP-DM methodology and leverages various models to classify high- vs low-risk borrowers.

# 📌 Project Methodology
This project follows the CRISP-DM (Cross Industry Standard Process for Data Mining) framework:

Business Understanding – Assess risk to improve lending decisions.

Data Understanding – Explore borrower history, loan status, and financial behavior.

Data Preparation – Clean, transform, and engineer features.

Modeling – Train various classification models.

Evaluation – Compare models and metrics.

# 📊 Dataset Assumptions
Historical financial data from a financial ecosystem.

Includes application metadata, credit performance, and transactional behavior.

Assumed to be representative of real customer interactions and reliable for risk modeling.

🧪 Modeling Pipeline
The notebook applies the following models:

Decision Tree Classifier

Naive Bayes

Support Vector Machine

AdaBoost

Gradient Boosting

Random Forest

Extra Trees

MLP (Neural Network)

# 📌 Data imbalance is handled using SMOTE (Synthetic Minority Oversampling Technique).

📊 Model evaluation includes:

Accuracy

F1 Score

ROC Curve / AUC

Cross-validation with stratified folds



