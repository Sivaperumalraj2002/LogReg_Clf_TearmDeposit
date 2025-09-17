📊 Bank Marketing Prediction with Logistic Regression

This project applies Logistic Regression to the UCI Bank Marketing Dataset
 to predict whether a customer subscribes to a term deposit based on their demographic and financial information.
 .
├── bank-additional-full.csv     # Dataset (UCI Bank Marketing)
├── main.ipynb                   # Jupyter Notebook with full workflow
└── README.md                    # Project documentation

📌 Problem Statement

Banks conduct marketing campaigns to promote term deposits. However, identifying the right customers to target is challenging. This project aims to:

Build a classification model using Logistic Regression.

Predict if a customer will subscribe to a term deposit (yes/no).

Provide insights into customer demographics and financial behavior.

🛠️ Methodology

Data Preprocessing

Handled categorical variables with Label Encoding.

Cleaned and prepared dataset for ML.

Exploratory Data Analysis (EDA)

Studied relationships between age, job type, marital status, education, loan status, and outcome.

Checked campaign-related features like contact type, duration, and previous outcomes.

Model Building

Trained a Logistic Regression classifier using Scikit-learn.

Split dataset into train/test for evaluation.

Model Evaluation

Accuracy Score

(Optional) Confusion Matrix, ROC-AUC for deeper insights.

📈 Results

The Logistic Regression model successfully predicted term deposit subscriptions.

Accuracy was measured on test data (see notebook for details).

The model highlights the importance of features such as contact type, campaign duration, and economic indicators.
