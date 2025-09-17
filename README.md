**SMS Spam Detection**

This project focuses on building a machine learning application that detects whether an SMS message is Spam or Ham (Not Spam).
The solution uses Natural Language Processing (NLP) for text preprocessing and multiple ML algorithms for classification.
Additionally, a Streamlit web app is included to provide users with an interactive way to test SMS messages in real time.

---

 
 **Features**

* Spam Prediction – Enter an SMS message and instantly get predictions.

* Multiple ML Models – Compare results from different algorithms.

* Model Evaluation – Accuracy scores, confusion matrices, and reports included.

* User-Friendly Web App – Powered by Streamlit.

---

**Models Implemented**

* Logistic Regression

* Support Vector Machine (SVM)

* Random Forest Classifier

* Gradient Boosting Classifier

* Multinomial Naive Bayes
---

**Installation**

1️.Clone the Repository

git clone https://github.com/your-username/SMS-Spam-Detection.git

cd SMS-Spam-Detection

2️.Create and Activate Virtual Environment

For Windows:

python -m venv venv

venv\Scripts\activate

For Mac/Linux:

python3 -m venv venv
source venv/bin/activate

3️.Install Dependencies

pip install -r requirements.txt

4.Download Required NLTK Resources

import nltk

nltk.download("stopwords")

nltk.download("wordnet")

5.Run the application : streamlit run app.py

---

**License**
This project is licensed under the MIT License
