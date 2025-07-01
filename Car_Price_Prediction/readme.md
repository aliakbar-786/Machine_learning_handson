Car Price Prediction using Linear Regression & One-Hot Encoding
This project demonstrates how to predict car prices using Linear Regression, while handling categorical features like "Brand" with One-Hot Encoding, all wrapped inside a clean Scikit-Learn Pipeline.

🛠 Tech Stack
Python 🐍

Pandas (Data Handling)

Scikit-Learn (Model Building & Preprocessing)

📂 Project Files
 
Car_Price_Prediction/
├── car_price_prediction.py      # Main Script
├── car_prices.csv               # Dataset (Car details)
└── README.md                    # Project Instructions

📊 Dataset Example (car_prices.csv)

Age	Mileage	Brand	Price
3	40000	Toyota	15000
5	60000	Honda	12000
2	30000	BMW	25000
...	...	...	...

Age = Age of the car in years

Mileage = Total kilometers driven

Brand = Categorical feature (e.g., Toyota, Honda, BMW)

Price = Target value to predict

📌 How to Run
Clone the Repository

 
git clone https://github.com/aliakbar-786/Machine_learning_handson.git
cd Machine_learning_handson/Car_Price_Prediction
Install Requirements

 
pip install pandas scikit-learn
Run the Script

 
python car_price_prediction.py
🧠 Key Steps in the Project
✅ Data Loading with Pandas
✅ Splitting features & target
✅ One-Hot Encoding for categorical column (Brand)
✅ Building Scikit-Learn Pipeline (Preprocessing + Model)
✅ Train-Test Split
✅ Linear Regression Model Training
✅ Model Evaluation using Mean Squared Error (MSE) & R2 Score

📈 Example Output
python-repl
 
   Age  Mileage   Brand  Price
0    3    40000  Toyota  15000
1    5    60000   Honda  12000
2    2    30000     BMW  25000
...

Mean Squared Error (MSE): 1625000.45
R2 Score: 0.87
🎯 Learning Highlights
Handling Mixed Data (Categorical + Numeric)

Using ColumnTransformer for targeted preprocessing

Full Pipeline for clean, reproducible ML workflow

Model evaluation with standard metrics

