# 🎬 Movie Genre Analysis & Recommendation System

This project explores and models a dataset of 9,400+ movies using Natural Language Processing (NLP) techniques. It covers genre analysis, keyword extraction, multi-label classification, clustering, and a content-based movie recommender system — all driven by movie plot descriptions.

---

📁 Dataset Overview

- Total Movies: 9,420
- Unique Titles: 9,087
- Genres: 9,411 unique combinations (multi-label)
- Fields:
  - `movie_name`: Movie title
  - `genre`: Comma-separated list of genres
  - `description`: Movie plot synopsis

---

 🔍 Key Features

 📊 1. Exploratory Data Analysis (EDA)
- Genre frequency distribution
- Top genres and their counts
- Keyword frequency from plot descriptions

 🧠 2. NLP + Machine Learning
- **TF-IDF Vectorization** of movie descriptions
- **Single-label genre prediction** using Logistic Regression
- **Multi-label genre classification** with Random Forest (One-vs-Rest strategy)
- Evaluation metrics: Classification Report, Hamming Loss, Subset Accuracy

🧪 3. Unsupervised Clustering
- KMeans clustering of movie descriptions
- 2D PCA visualization of clusters
- Top TF-IDF keywords per cluster

 🎯 4. Content-Based Recommender
- Recommends movies based on plot similarity
- Uses cosine similarity on TF-IDF vectors
- Example: Get similar movies to *The Godfather*

---

