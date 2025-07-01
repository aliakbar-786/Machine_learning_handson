💳 Credit Card Fraud Detection – Classification
This project demonstrates how to detect fraudulent credit card transactions using a Random Forest Classifier wrapped inside a clean Scikit-Learn Pipeline. Categorical features like transaction type and location are handled with One-Hot Encoding, and model evaluation is done with standard classification metrics.

🛠 Tech Stack
Python 🐍

Pandas (Data Handling)

Scikit-Learn (Preprocessing & Machine Learning)

📂 Project Structure
 
Credit_Card_Fraud_Detection/
├── credit_card_fraud_detection.py      # Main ML Script
├── credit_card_fraud.csv               # Dataset (Transaction Details)
└── README.md                           # Project Instructions

📊 Dataset Example (credit_card_fraud.csv)


transaction_type	location	card_present	amount	hour	fraud
Online	US	Yes	120.50	14	0
POS	UK	No	250.00	19	1
ATM	US	Yes	80.00	9	0
...	...	...	...	...	...

fraud = 1 ➡️ Fraudulent Transaction

fraud = 0 ➡️ Legitimate Transaction

📌 How to Run
Navigate to the Project Folder

 
cd Credit_Card_Fraud_Detection
Install Dependencies

 
pip install pandas scikit-learn
Run the Script
 
python credit_card_fraud_detection.py

🧠 Project Workflow
✅ Load transaction dataset
✅ Separate features & target (fraud)
✅ One-Hot Encode categorical features (transaction_type, location, card_present)
✅ Combine preprocessing and model training using Scikit-Learn Pipeline
✅ Train a Random Forest Classifier
✅ Evaluate model with Accuracy & Classification Report

🔧 Why Preprocessing Matters
ML models require numeric input

OneHotEncoder transforms categorical columns to numeric format

Pipeline ensures clean, organized workflow (preprocessing + model training in one step)

📈 Example Output
 
  transaction_type  location  card_present  amount  hour  fraud
0           Online        US           Yes  120.50    14      0
1               POS        UK            No 250.00    19      1
...

Accuracy: 0.94
Classification Report:
              precision    recall  f1-score   support

           0       0.96      0.97      0.96       500
           1       0.89      0.86      0.87       100

    accuracy                           0.94       600
   macro avg       0.93      0.91      0.92       600
weighted avg       0.94      0.94      0.94       600