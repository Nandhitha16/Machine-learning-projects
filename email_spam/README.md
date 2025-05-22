# Machine-learning-projects
# Spam-Ham Email Classifier
# 📧 Spam-Ham Email Classifier

This project is a machine learning-based email classifier that detects whether a given message is **Spam** or **Ham** using a **Naive Bayes classifier** trained on SMS/email text data. It features an intuitive web interface powered by **Streamlit**.

---

## 🚀 Features

- ✅ Text preprocessing and vectorization using CountVectorizer
- 🤖 Classification using Multinomial Naive Bayes
- 🌐 Deployed using Streamlit web app
- 📂 Modular structure for future additions:
  - Job scraping module
  - Skill-based job clustering
  - Alerting users for matching job profiles

---

## 📂 Project Structure
spam-ham-classifier/
│
├── app.py # Streamlit app to classify text
├── data/
│ └── spam.csv # Labeled dataset for spam detection
├── model/
│ ├── naive_bayes_model.pkl # Trained Naive Bayes model
│ └── count_vectorizer.pkl # Fitted CountVectorizer
├── notebooks/
│ └── Spam_detection__NB.ipynb # Notebook for training and evaluation
├── utils/
│ └── preprocess.py # Text preprocessing functions (optional)
├── scraping/ # Placeholder for job scraping logic
│ └── job_scraper.py # (Optional) Web scraper for job postings
├── cluster/ # Placeholder for skill clustering logic
│ └── cluster_skills.py # (Optional) Clustering based on skills
├── alert/ # Placeholder for alerting users
│ └── alert.py # (Optional) Email/notification system
├── requirements.txt # Python dependencies
└── README.md # Project documentation
