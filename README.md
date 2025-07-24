# 🎬 Movie Recommendation System

This is a content-based movie recommendation system built using **Python** and **Streamlit**, using the TMDB Top Rated Movies dataset.

## 🔍 Project Overview

This app recommends similar movies based on the description and genre of a selected movie. It uses **natural language processing** techniques and **cosine similarity** to find movies with similar content.

## 📁 Dataset

- Source: [Kaggle TMDB Top Rated Movies](https://www.kaggle.com/datasets/ahsanaseer/top-rated-tmdb-movies-10k)
- Features used: `title`, `overview`, `genre`

## 🧠 Methodology

1. Data Cleaning & Feature Engineering
2. Tag Creation: `overview` + `genre` columns combined
3. Vectorization using `CountVectorizer` (NLP)
4. Cosine Similarity Matrix for Recommendations

## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn
- Streamlit

