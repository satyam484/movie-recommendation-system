# 🎬 Movie Recommendation System

## 📌 Overview
This project is a content-based movie recommendation system that suggests similar movies based on textual features such as genres, keywords, and descriptions using Natural Language Processing (NLP) techniques.

---

## 🎯 Objective
To build a recommendation system that provides personalized movie suggestions by analyzing similarities between movies.

---

## 📊 Dataset
- Movie metadata dataset (titles, genres, keywords, overview)
- Preprocessed textual features for similarity computation

---

## ⚙️ Approach

### 1. Data Preprocessing
- Tokenization
- Stemming
- Removal of stopwords
- Text cleaning using regex

### 2. Feature Engineering
- Combined relevant textual features
- Applied **TF-IDF Vectorization**

### 3. Similarity Calculation
- Used **Cosine Similarity** to compute similarity between movies

---

## 🧠 Model Details
- Content-based filtering approach
- No user interaction data required
- Efficient similarity-based recommendations

---

## 📈 Results
- Generated relevant movie recommendations based on similarity scores
- Improved recommendation quality through parameter tuning

---

## 🚀 How to Run

```bash
git clone https://github.com/satyam484/movie-recommendation-system.git
cd movie-recommendation-system
pip install -r requirements.txt
python app.py
