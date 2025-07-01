🌫️ Air Quality Index (AQI) Forecasting – Regression
This project predicts the Air Quality Index (AQI) using various air pollutant levels with a Linear Regression model. It demonstrates how to build a basic regression model to forecast environmental health indicators based on pollution data.

🛠 Tech Stack
Python 🐍

Pandas (Data Handling)

Scikit-Learn (Model Training & Evaluation)

📂 Project Structure
 
AQI_Forecasting/
├── air_quality_forecasting.py       # Main Regression Script
├── air_quality.csv                  # Air Quality Dataset
└── README.md                        # Project Instructions

📊 Dataset Example (air_quality.csv)

PM2.5	PM10	NO2	SO2	CO	O3	AQI
56.2	95.3	42	8.1	0.5	23	120
72.5	110	50	9.3	0.6	19	145
34.7	70.1	30	5.2	0.4	26	95
...	...	...	...	...	...	...

PM2.5, PM10, NO2, SO2, CO, O3 = Pollutant Concentrations

AQI = Air Quality Index (target to predict)

📌 How to Run
Navigate to the Project Folder

cd AQI_Forecasting
Install Dependencies

pip install pandas scikit-learn
Run the Script


python air_quality_forecasting.py

🧠 Project Workflow
✅ Load air quality dataset with pollutant levels
✅ Define features (pollutants) and target (AQI)
✅ Split data into training and testing sets
✅ Train a Linear Regression model
✅ Evaluate model with Mean Squared Error (MSE) and R2 Score
✅ Compare predicted AQI with actual AQI

📈 Example Output

   PM2.5   PM10  NO2  SO2   CO   O3  AQI
0   56.2   95.3   42  8.1  0.5  23  120
1   72.5  110.0   50  9.3  0.6  19  145
...

Mean Squared Error (MSE): 128.56
R2 Score (Accuracy jesa): 0.87

Actual AQI: 130
Predicted AQI: 127.45
