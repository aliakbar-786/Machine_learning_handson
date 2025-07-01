🏠 House Price Prediction with Linear Regression & One-Hot Encoding
This project predicts house prices using Linear Regression, handling both numeric and categorical features with Scikit-Learn's ColumnTransformer and Pipeline. It demonstrates a clean, production-friendly workflow for preprocessing and model training.

🛠 Tech Stack
Python 🐍

Pandas (Data Handling)

Scikit-Learn (Preprocessing, Model Building)

📂 Project Structure
 
House_Price_Prediction/
├── house_price_prediction.py      # Main ML Script
├── house_prices.csv               # Dataset (House details)
└── README.md                      # Project Instructions

📊 Dataset Example (house_prices.csv)

Rooms	Area	Age	Location	Price
3	1200	5	Lahore	8500000
4	1500	2	Karachi	12000000
2	900	8	Lahore	6000000
...	...	...	...	...

Rooms = Total rooms in the house

Area = Area in square feet

Age = House age in years

Location = Categorical feature (e.g., Lahore, Karachi)

Price = House price to predict

📌 How to Run
Navigate to the Project Folder

 
cd House_Price_Prediction
Install Dependencies

 
pip install pandas scikit-learn
Run the Script

 
python house_price_prediction.py
🧠 Project Workflow
✅ Load Dataset with Pandas
✅ Separate Features & Target
✅ One-Hot Encode Categorical Data (Location)
✅ Combine Preprocessing & Model with Pipeline
✅ Train-Test Split for evaluation
✅ Linear Regression Model Training
✅ Evaluate using Mean Squared Error & R2 Score

