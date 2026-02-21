
# 📚 Text Classification using Naive Bayes

This project demonstrates how to build a **Text Classification system** using the **Naive Bayes algorithm** in Python. The model classifies text documents into predefined categories based on word probabilities using **Bayes’ Theorem**.

The classifier is trained on a synthetic dataset containing short text samples categorized into:

* 🖥 Technology
* 🏏 Sports
* 🏛 Politics
* 🎬 Entertainment


## 🚀 Project Overview

Naive Bayes is a popular and efficient probabilistic algorithm widely used in **Natural Language Processing (NLP)** tasks such as:

* Spam detection
* Sentiment analysis
* News categorization
* Document classification

In this project, I use **Multinomial Naive Bayes**, which is well-suited for text classification problems where features represent word counts.



## 🛠️ Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn


## 📂 Dataset

The dataset (`synthetic_text_data.csv`) contains:

* `text` → A short sentence or statement
* `label` → Category (Technology, Sports, Politics, Entertainment)

Example:

| Text                          | Label      |
| ----------------------------- | ---------- |
| AI is transforming the world  | Technology |
| The team won the championship | Sports     |






## 📊 Results

* The model achieved **~88% accuracy**.
* Most predictions were correct.
* Some minor misclassifications occurred between related categories.





## 🎯 Future Improvements

* Use **TF-IDF Vectorizer**
* Apply **Hyperparameter Tuning**
* Add larger real-world dataset
* Implement GUI or Web App (Streamlit/Flask)
* Compare with Logistic Regression or SVM


