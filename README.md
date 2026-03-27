# 📰 Fake News Detection using Machine Learning

## 📌 Project Overview

This project focuses on building a **machine learning model to classify news articles as real or fake** based on textual content. The pipeline includes **data preprocessing, feature engineering, text transformation, model training, and evaluation**.

---

## 📂 Dataset Description

The dataset contains the following features:

* **id** – Unique identifier for each news article
* **title** – Title of the news article
* **author** – Author of the article
* **text** – Full or partial content of the article
* **label** – Target variable

  * `0` → Real News
  * `1` → Fake News

---

## ⚙️ Steps Performed

### 🔹 Data Preprocessing

* Loaded dataset into a DataFrame
* Checked and printed **English stopwords**
* Replaced missing values with empty strings
* Merged **author name + news title** into a single feature

---

### 🔹 Text Processing

* Applied **stemming** to reduce words to root form
  *(Example: "running" → "run")*
* Removed stopwords to improve model performance

---

### 🔹 Feature Engineering

* Separated **features (X)** and **labels (y)**
* Converted textual data into numerical form using **vectorization techniques**

---

### 🔹 Model Building

* Split dataset into:

  * Training set
  * Testing set
* Trained a classification model on processed data

---

### 🔹 Model Evaluation

* Evaluated model using:

  * Accuracy Score
* Verified model performance on test dataset

---

## 🤖 Predictive System

Built a predictive system that takes **news input** and classifies it as:

* ✅ Real News
* ❌ Fake News

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP)

---

## 📊 Workflow

```
Data Collection
↓
Data Cleaning
↓
Text Preprocessing (Stopwords + Stemming)
↓
Feature Extraction (Vectorization)
↓
Train-Test Split
↓
Model Training
↓
Model Evaluation
↓
Prediction System
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```
https://github.com/knagaraj-2106
```

2. Navigate to project folder:

```
cd fake-news-detection
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run the notebook or script:

```
python main.py
```

---

## 📈 Results

* Successfully built a classification model for fake news detection
* Achieved reliable accuracy on test data
* Demonstrated end-to-end ML pipeline implementation

---

## 📌 Future Improvements

* Improve model accuracy using advanced algorithms
* Use deep learning models (LSTM, BERT)
* Deploy using API for real-time prediction
* Add UI for user interaction
