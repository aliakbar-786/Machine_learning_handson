🚢 Titanic Survival Prediction – Classification
This project predicts passenger survival on the Titanic using a Random Forest Classifier. The dataset includes demographic and travel information, and demonstrates preprocessing techniques like Label Encoding, missing value handling, and evaluation with classification metrics.

🛠 Tech Stack
Python 🐍

Pandas (Data Handling)

Scikit-Learn (Preprocessing, Modeling, Evaluation)

📂 Project Structure
 
Titanic_Survival_Prediction/
├── titanic_survival_prediction.py    # Main ML Script
├── titanic.csv                       # Dataset (Passenger Details)
└── README.md                         # Project Instructions

📊 Dataset Example (titanic.csv)

Pclass	Sex	Age	SibSp	Parch	Fare	Survived
3	male	22	1	0	7.25	0
1	female	38	1	0	71.28	1
3	female	26	0	0	7.92	1
...	...	...	...	...	...	...

Survived = 1 ➡️ Passenger Survived

Survived = 0 ➡️ Passenger Did Not Survive

📌 How to Run
Navigate to the Project Folder


cd Titanic_Survival_Prediction
Install Dependencies

 
pip install pandas scikit-learn
Run the Script

 
python titanic_survival_prediction.py

🧠 Project Workflow
✅ Load the Titanic dataset
✅ Select relevant columns and handle missing values
✅ Encode categorical column (Sex) using LabelEncoder
✅ Define features and target (Survived)
✅ Split data into training and testing sets
✅ Train a Random Forest Classifier
✅ Evaluate with Accuracy & Classification Report

🔧 Quick Notes
Encoder Type	When to Use	Example Columns
LabelEncoder	For binary categories	Sex, Survived
OneHotEncoder	For 3+ categories (no order)	City, Color

Axis Meaning in Pandas:
Axis	Meaning
axis=0	Operates row-wise
axis=1	Operates column-wise

📈 Example Output
markdown
 
Accuracy: 0.82
Classification Report:
              precision    recall  f1-score   support

           0       0.83      0.85      0.84        23
           1       0.80      0.78      0.79        18

    accuracy                           0.82        41
   macro avg       0.82      0.82      0.82        41
weighted avg       0.82      0.82      0.82        41

🎯 Learning Highlights
✅ Real-world dataset for binary classification
✅ Handling categorical variables with encoding
✅ Evaluating models with common classification metrics
✅ Missing value handling and data cleaning