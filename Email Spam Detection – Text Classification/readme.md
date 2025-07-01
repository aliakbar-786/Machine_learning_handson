📧 Email Spam Detection – Text Classification
This project builds a simple Spam vs. Ham (Not Spam) classifier using a Naive Bayes Model and TF-IDF Vectorization. It demonstrates how to convert text into numerical form so machine learning models can process and classify emails.

🛠 Tech Stack
Python 🐍

Pandas (Data Handling)

Scikit-Learn (Text Processing & Machine Learning)

📂 Project Structure
 
Email_Spam_Detection/
├── email_spam_detection.py           # Main ML Script
└── README.md                         # Project Instructions

📊 Dataset Example (Sample Used)
Text	Label
"Win money now!"	spam
"Your account is suspended"	spam
"Hi, how are you?"	ham
"Meeting tomorrow at 10"	ham
...	...

spam ➡️ Unwanted or harmful message

ham ➡️ Legitimate message

📌 How to Run
Navigate to the Project Folder
 
cd Email_Spam_Detection
Install Dependencies
 
pip install pandas scikit-learn
Run the Script

python email_spam_detection.py
🧠 Project Workflow
✅ Load dataset (sample included, replace with your real email data if needed)
✅ Convert text data to numerical format using TF-IDF Vectorizer
✅ Split data into training and testing sets
✅ Train a Multinomial Naive Bayes model
✅ Evaluate with Accuracy & Classification Report

🤔 Why TF-IDF Vectorizer?
Machine learning models only understand numbers, not raw text

TF-IDF (Term Frequency-Inverse Document Frequency) assigns weight to words

Rare & informative words get higher importance

Common words like "the", "is", etc., get lower importance

📈 Example Output
 
Accuracy: 1.0
Classification Report:
              precision    recall  f1-score   support

         ham       1.00      1.00      1.00         2
        spam       1.00      1.00      1.00         2

    accuracy                           1.00         4
   macro avg       1.00      1.00      1.00         4
weighted avg       1.00      1.00      1.00         4

🎯 Learning Highlights
✅ Text classification using TF-IDF
✅ Simple Naive Bayes model for spam detection
✅ Converting text into machine-readable format
✅ Evaluating performance with standard metrics

