Loan Eligibility Prediction using DecisionTreeClassifier

📌 Project Overview

This project develops a loan eligibility prediction model using the Decision Tree Classifier. The model determines whether a client is eligible for a loan based on personal and financial data.

📂 Dataset Information

The dataset consists of 45,000 entries and 14 columns, including:

Column Name

Description

person_age

Age of the client

person_gender

Gender of the client

person_education

Educational background

person_income

Monthly income of the client

person_emp_exp

Years of employment experience

person_home_ownership

Home ownership status (Rent, Own, Mortgage, etc.)

loan_amnt

Requested loan amount

loan_intent

Purpose of the loan

loan_int_rate

Interest rate assigned to the loan

loan_percent_income

Loan amount as a percentage of income

cb_person_cred_hist_length

Credit history length (in years)

credit_score

Client’s credit score

previous_loan_defaults_on_file

Previous loan defaults (Yes/No)

loan_status

Target variable: 1 (Loan Approved), 0 (Loan Denied)

🛠️ Technologies Used

Python for scripting

Pandas & NumPy for data processing

Scikit-Learn for machine learning

Matplotlib & Seaborn for data visualization

🔍 Key Steps in Development

1️⃣ Data Preprocessing

Handling missing values (if any)

Encoding categorical variables (one-hot encoding & label encoding)

Splitting the dataset into train (80%) and test (20%) sets

Feature scaling where necessary

2️⃣ Model Development

Using DecisionTreeClassifier from Scikit-Learn

Training the model on the dataset

Optimizing hyperparameters (e.g., max_depth, min_samples_split, etc.)

3️⃣ Model Evaluation

Evaluating performance using:

Accuracy score

Precision, Recall, F1-Score

Confusion Matrix

ROC Curve

4️⃣ Making Predictions

Using the trained model to predict loan eligibility for new clients

🚀 How to Run the Project

1️⃣ Install Dependencies

pip install pandas numpy scikit-learn matplotlib seaborn

2️⃣ Run the Training Script

python train_model.py

3️⃣ Make Predictions

python predict.py

📈 Example Results

Training Accuracy: ~85%

Test Accuracy: ~83%

Precision, Recall, and F1-score values indicating model performance

📌 Key Takeaways

Decision Trees provide interpretable results but can be prone to overfitting.

Feature selection plays a critical role in improving model accuracy.

Further improvements can be made using Random Forest or XGBoost.

🔗 Future Improvements

Implement Random Forest for better generalization.

Use GridSearchCV for hyperparameter tuning.

Deploy the model using Flask or FastAPI.
