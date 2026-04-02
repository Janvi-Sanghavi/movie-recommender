# 🎬 Hybrid Movie Recommendation System

## 📌 Overview
This project builds a hybrid movie recommendation system using:
- Content-Based Filtering (TF-IDF, Cosine Similarity)
- Collaborative Filtering (User-User Similarity)

## 🚀 Features
- Recommends movies based on content similarity
- Uses user behavior for personalized recommendations
- Handles cold-start problem using fallback strategy
- Fully dynamic input (user ID + movie name)

## 🧠 Tech Stack
- Python
- Pandas
- Scikit-learn

## 📊 Datasets Used
- MovieLens (ratings, movies)
- TMDB 5000 Movie Dataset

## ⚙️ How It Works
1. Content-Based Filtering → Finds similar movies
2. Collaborative Filtering → Finds similar users
3. Hybrid Model → Combines both for ranking

## ▶️ Run the Project

```bash
pip install -r requirements.txt
