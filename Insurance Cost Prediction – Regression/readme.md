💼 Insurance Cost Prediction – Regression
This project predicts medical insurance charges based on factors like age, BMI, smoking habits, and region using a Linear Regression model. Categorical data is handled with One-Hot Encoding, and the entire workflow is wrapped inside a clean Scikit-Learn Pipeline.

🛠 Tech Stack
Python 🐍

Pandas (Data Handling)

Scikit-Learn (Preprocessing & Model Building)

📂 Project Structure
 
Insurance_Cost_Prediction/
├── insurance_cost_prediction.py      # Main ML Script
├── insurance.csv                     # Dataset (Customer details)
└── README.md                         # Project Instructions

📊 Dataset Example (insurance.csv)

age	sex	bmi	children	smoker	region	charges
19	female	27.9	0	yes	southwest	16884.9
35	male	25.3	2	no	northwest	6455.0
45	female	30.5	1	yes	southeast	42300.0
...	...	...	...	...	...	...

📌 How to Run
Navigate to the Project Folder

cd Insurance_Cost_Prediction
Install Dependencies

pip install pandas scikit-learn
Run the Script

python insurance_cost_prediction.py

🧠 Project Workflow
✅ Load dataset with personal & lifestyle details
✅ Define input features and target (insurance charges)
✅ Handle categorical features with One-Hot Encoding
✅ Use Scikit-Learn Pipeline to combine preprocessing & model training
✅ Train a Linear Regression model
✅ Evaluate model using MSE and R2 Score
✅ Compare actual vs predicted insurance costs

📈 Example Output

   age     sex   bmi  children smoker     region   charges
0   19  female  27.9         0    yes  southwest  16884.92
1   35    male  25.3         2     no  northwest   6455.00
...

Mean Squared Error (MSE): 35000000.45
R2 Score (Model ki accuracy jesa): 0.79

Actual Charges: 27000.35
Predicted Charges: 26540.27
