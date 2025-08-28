🔎 Overview

This project focuses on building a machine learning application that detects whether an SMS message is Spam or Ham (Not Spam).
The solution uses Natural Language Processing (NLP) for text preprocessing and multiple ML algorithms for classification.
Additionally, a Streamlit web app is included to provide users with an interactive way to test SMS messages in real time.

✨ Features

Spam Prediction – Enter an SMS message and instantly get predictions.

Multiple ML Models – Compare results from different algorithms.

Model Evaluation – Accuracy scores, confusion matrices, and reports included.

User-Friendly Web App – Powered by Streamlit.

🤖 Models Implemented

Logistic Regression

Support Vector Machine (SVM)

Random Forest Classifier

Gradient Boosting Classifier

Multinomial Naïve Bayesowered by Streamlit.

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/Prethika88/SMS-Spam-Detection.git
cd SMS-Spam-Detection

2️⃣ Create and Activate Virtual Environment

For Windows:

python -m venv venv
venv\Scripts\activate

For Mac/Linux:

python3 -m venv venv
source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Download Required NLTK Resources

Run in Python:

import nltk
nltk.download("stopwords")
nltk.download("wordnet")

▶️ Running the App

Start the Streamlit web application:

streamlit run app.py
