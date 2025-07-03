# 🏨 Hotel Review Topic Modeling using NLP, TF-IDF and NMF

This project applies unsupervised NLP techniques to uncover hidden topics in hotel reviews from the [Tripadvisor dataset](#). We use **TF-IDF vectorization** and **Non-negative Matrix Factorization (NMF)** to identify what customers most frequently talk about – such as cleanliness, staff, location, and more.

---

## 📌 Objective

The goal is to extract **meaningful topics** from raw textual reviews, without any labels, to help:
- Understand what customers care about
- Identify common praise and complaints
- Support hotel managers in improving services

---

## 🧾 Dataset

- `tripadvisor_hotel_reviews.csv`
- Contains:
  - `Review`: Text review by customer
  - `Rating`: Integer from 1 to 5 (optional in topic modeling)

---

## 🛠️ Project Steps

### 1. Exploratory Data Analysis (EDA) 🧪 *(Optional)*
- Distribution of `Rating`
- Length of reviews (word count)

### 2. Text Preprocessing 🔧
- Lowercasing text  
- Removing punctuation and numbers  
- Removing stopwords (using NLTK)  
- Lemmatization of words  

### 3. Feature Extraction 🧠
- **TF-IDF** is used to convert text into numerical features, capturing importance of words.

### 4. Topic Modeling 📊
- **NMF (Non-negative Matrix Factorization)** is applied to discover hidden topics.
- Top keywords are extracted for each topic.

### 5. (Optional) Topic Assignment & Visualization 📈
- Each review is assigned to the closest topic.
- Pie chart or bar chart shows topic distribution.
- WordClouds for each topic (optional).

---

## 📎 Sample Output

Topic 1: room | clean | bed | bathroom | comfortable | spacious | shower | towel | smell | dirty
Topic 2: staff | helpful | friendly | service | reception | polite | desk | check | professional | kind

