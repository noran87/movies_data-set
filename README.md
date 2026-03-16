
# Movie Data Analysis & Recommendation Projects

This repository contains three data projects exploring movie datasets using Python, Pandas, visualization libraries, and basic machine learning techniques.

The goal of these projects is to practice real-world data workflows including:
- Data cleaning
- Exploratory data analysis (EDA)
- Data visualization
- Recommendation systems
- Basic machine learning concepts

---

# Project 1: Netflix Exploratory Data Analysis

Dataset: Netflix Titles

This project explores the Netflix dataset to understand patterns in movie and TV show releases.

Key work:
- Cleaned messy columns such as `duration`, `date_added`, `country`, `rating`, and `listed_in`
- Converted text fields into structured data
- Handled missing values
- Created new columns such as year added and month added

Analysis included:
- Netflix content growth over time
- Movies vs TV shows distribution
- Genre trends over time
- Genre comparison between Movies and TV Shows

Tools used:
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# Project 2: IMDB Top 1000 Movies Analysis

Dataset: IMDB Top 1000 Movies

This project analyzes relationships between movie ratings, popularity, and genres.

Data cleaning tasks:
- Converted `Released_Year` to numeric format
- Handled missing values in `Certificate`, `Subgenre`, `Meta_score`, and `Gross`
- Standardized genre-related columns

Analysis included:
- Do higher rated movies make more money?
- Relationship between number of votes and ratings
- Distribution of votes across rating tiers
- Most voted movies on IMDB
- Which genres receive the most audience votes

Tools used:
- Pandas
- Matplotlib
- Seaborn

---

# Project 3: Movie Recommendation System (Machine Learning)

Dataset: IMDB Top 1000 Movies

This project builds a content-based movie recommender.

Steps:
1. Combine movie metadata (genre, subgenres, actors, director) into a text feature
2. Convert text into numeric vectors using TF‑IDF
3. Compute similarity between movies using cosine similarity
4. Recommend movies based on similarity scores

Core ML concepts used:
- TF‑IDF Vectorization
- Cosine Similarity
- Similarity Matrix
- Content-based recommendation

The recommender works by comparing movie content and returning the most similar movies to the selected title.

Tools used:
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity

---

# Repository Structure

data/
- datasets used for the projects

notebooks/
- netflix_eda.ipynb
- imdb_analysis.ipynb
- movie_recommender_ml.ipynb

---

# Conclusion

These projects demonstrate a learning progression:

1. Data cleaning and exploration
2. Analytical insights from datasets
3. Building a simple machine learning recommendation system

The projects helped develop practical skills in data analysis, Python programming, and introductory machine learning techniques.
