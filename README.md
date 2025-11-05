# 🗣️ Yelp Review Sentiment Classification (NLP Project)

This project applies **Natural Language Processing (NLP)** and **machine learning** to classify **Yelp reviews** as either **positive (5-star)** or **negative (1-star)** based on their textual content.

Using the **Yelp Review Dataset** from Kaggle, this project demonstrates how to clean, preprocess, and model text data efficiently with **scikit-learn pipelines** — allowing for an elegant and scalable workflow.

---

## 📘 Project Overview

Yelp provides user-generated reviews for businesses such as restaurants, salons, and services.  
Each review includes:
- **Text content** — the actual review text
- **Stars (1–5)** — user rating for the business  
- **Votes** — “cool”, “useful”, and “funny” counts from other users

Our goal is to:
> Build a model that predicts whether a review is **1 star (negative)** or **5 stars (positive)** from its text.

This project simplifies the sentiment classification process by focusing only on extreme ratings (1 and 5), creating a clear distinction for model training.

---

## 🧠 Key Concepts

- **Text preprocessing** with `CountVectorizer` and `TfidfTransformer`  
- **Machine Learning Pipelines** for modular model building  
- **Binary text classification** using logistic regression  
- **Model evaluation** with accuracy, confusion matrix, and classification report  

---

## 🧩 Technologies Used

- **Python 3.10+**  
- **scikit-learn**  
- **pandas**  
- **NumPy**  
- **Matplotlib / Seaborn**  
- **Jupyter Notebook**

---

## 🚀 Project Workflow

1. **Data Loading**  
   - Load the Yelp dataset using `pandas`.  
   - Filter data for only 1-star and 5-star reviews.  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize class distribution.  
   - Inspect common words and review lengths.

3. **Text Preprocessing**  
   - Tokenization, stopword removal, and normalization.  
   - Convert text to numerical features using **TF-IDF**.

4. **Model Building**  
   - Create an **NLP pipeline** combining `CountVectorizer`, `TfidfTransformer`, and a classifier (e.g., Logistic Regression).  
   - Train and validate the model.

5. **Evaluation**  
   - Assess model accuracy, confusion matrix, and classification report.  
   - Test model predictions on new unseen reviews.

---

