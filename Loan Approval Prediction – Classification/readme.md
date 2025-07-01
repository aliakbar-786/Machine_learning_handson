🏦 Loan Approval Prediction – Classification
This project predicts whether a loan application will be approved or not using a Random Forest Classifier and Scikit-Learn Pipelines. It demonstrates how to handle mixed data types (categorical + numeric) using preprocessing pipelines and evaluates the model with standard classification metrics.

🛠 Tech Stack
Python 🐍

Pandas (Data Handling)

Scikit-Learn (Preprocessing & Model Building)

📂 Project Structure
 
Loan_Approval_Prediction/
├── loan_approval_prediction.py      # Main ML Script
├── loan_approval.csv                # Dataset (Loan Application Details)
└── README.md                        # Project Instructions 

📊 Dataset Example (loan_approval.csv)
Gender	Married	Dependents	Education	Self_Employed	ApplicantIncome	CoapplicantIncome	LoanAmount	Loan_Amount_Term	Credit_History	Property_Area	Loan_Status
Male	Yes	0	Graduate	No	5000	0	130	360	1	Urban	Y
Female	No	1	Not Graduate	Yes	3000	1500	100	360	0	Rural	N
...	...	...	...	...	...	...	...	...	...	...	...

Loan_Status = Target column (Y = Approved, N = Not Approved)

📌 How to Run
Navigate to the Project Folder

 
cd Loan_Approval_Prediction
Install Dependencies

 
pip install pandas scikit-learn
Run the Script

 
python loan_approval_prediction.py
🧠 Project Workflow
✅ Load and explore the dataset
✅ Separate features and target
✅ Identify categorical & numeric columns
✅ Apply One-Hot Encoding to categorical data
✅ Build a Scikit-Learn Pipeline for preprocessing + model
✅ Train a Random Forest Classifier
✅ Evaluate with Accuracy & Classification Report

🔧 Key Concepts
OneHotEncoder: Converts categorical values (like Gender, Property_Area) into numeric format for model compatibility

Pipeline: Combines preprocessing and model training for clean, efficient code

Random Forest Classifier: An ensemble ML model for binary classification

📈 Example Output
 
   Gender  Married  Dependents  Education  Self_Employed  ApplicantIncome  CoapplicantIncome  LoanAmount  Loan_Amount_Term  Credit_History  Property_Area  Loan_Status
0    Male      Yes           0   Graduate             No             5000                  0         130               360               1           Urban            Y
...

Accuracy: 0.85
Classification Report:
              precision    recall  f1-score   support

           N       0.80      0.75      0.77        20
           Y       0.88      0.91      0.89        40

    accuracy                           0.85        60
   macro avg       0.84      0.83      0.83        60
weighted avg       0.85      0.85      0.85        60


🎯 Learning Highlights
✅ Data Preprocessing with Pipelines
✅ Handling Mixed Data Types (Categorical + Numeric)
✅ Building Classification Models with Random Forest
✅ Evaluating Binary Classification with Accuracy, Precision, Recall, F1