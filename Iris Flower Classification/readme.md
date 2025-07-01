🌸 Iris Flower Classification – Multi-Class Classification
This project classifies different species of Iris flowers using a Random Forest Classifier. The famous Iris dataset is used, which includes measurements of different flower features to predict the species.

🛠 Tech Stack
Python 🐍

Scikit-Learn (Dataset, Model Building, Evaluation)

📂 Project Structure
 
Iris_Flower_Classification/
├── iris_flower_classification.py     # Main ML Script
└── README.md                         # Project Instructions

📊 Dataset Overview (Iris Dataset)
The dataset contains measurements of 150 Iris flowers, divided into three species:

Setosa

Versicolor

Virginica

Features:
Feature	Description
Sepal Length (cm)	Length of the sepal
Sepal Width (cm)	Width of the sepal
Petal Length (cm)	Length of the petal
Petal Width (cm)	Width of the petal

📌 How to Run
Navigate to the Project Folder
 
cd Iris_Flower_Classification
Install Dependencies

 
pip install scikit-learn
Run the Script

 
python iris_flower_classification.py
🧠 Project Workflow
✅ Load the classic Iris dataset using Scikit-Learn
✅ Split the data into training and testing sets
✅ Train a Random Forest Classifier
✅ Predict species for test data
✅ Evaluate model using Accuracy, Confusion Matrix & Classification Report

📈 Example Output
 
Accuracy Score: 1.0
Confusion Matrix:
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]

Classification Report:
              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        10
  versicolor       1.00      1.00      1.00         9
   virginica       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30


🎯 Learning Highlights
✅ Multi-class classification problem
✅ Working with built-in Scikit-Learn datasets
✅ Model evaluation using various metrics
✅ Introduction to ensemble methods with Random Forest