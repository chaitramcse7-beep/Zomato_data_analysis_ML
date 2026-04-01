# Zomato_data_analysis_ML
# Project Overview

This project focuses on analyzing restaurant reviews from the Zomato dataset using **Machine Learning (ML)** and **Natural Language Processing (NLP)** techniques. The goal is to classify customer reviews into positive or negative sentiments and build an intelligent system that recommends similar restaurants based on customer feedback.

#Objectives

* Perform sentiment analysis on restaurant reviews
* Build and compare ML models for classification
* Evaluate model performance using metrics
* Develop a recommendation system based on review similarity

#  Features

* 🔹 Text preprocessing (cleaning, stopword removal)
* 🔹 TF-IDF vectorization for feature extraction
* 🔹 Sentiment classification (Positive / Negative)
* 🔹 Model comparison (Logistic Regression & Random Forest)
* 🔹 Confusion Matrix for evaluation
* 🔹 Custom prediction for user input
* 🔹 Content-based restaurant recommendation system

# Machine Learning Workflow

1. Data Loading (Zomato dataset)
2. Data Cleaning & Preprocessing
3. Text Vectorization using TF-IDF
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Recommendation System using Cosine Similarity

#Models Used

* Logistic Regression
* Random Forest Classifier

# Evaluation Metrics

* Accuracy Score
* Classification Report
* Confusion Matrix
# Recommendation System

The project implements a **content-based recommendation system**:

* Converts reviews into vectors using TF-IDF
* Uses cosine similarity to measure similarity
* Recommends top similar restaurants based on input

# Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

# Example

### Input:

> "The food was amazing and service was quick"

### Output:

> Positive 😊

---

### Recommendation Example:

Input:

> "domino"

Output:

> List of similar restaurants based on review patterns

---

## 📂 Project Structure

```id="3w5u0k"
├── Zomato_data_analysis.ipynb
├── dataset.csv
├── README.md
```

---

## 📌 Conclusion

This project demonstrates how machine learning and NLP techniques can be effectively used to analyze customer sentiments and provide intelligent restaurant recommendations. It highlights the practical application of data-driven decision-making in the food and hospitality industry.

---

## 🔮 Future Scope

* Implement deep learning models (LSTM, BERT)
* Build a web application using Streamlit
* Add user-based recommendation system
* Deploy the model for real-time predictions

---

## 👤 Author

**Moolya Chaitra Satish**

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
