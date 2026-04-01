# 🎬 Movie Data Analysis & Machine Learning Portfolio

This repository contains a collection of projects focused on exploring movie datasets using Python, data analysis, and machine learning techniques.

The goal of this repository is to demonstrate a clear learning progression:
- Data cleaning and preparation
- Exploratory data analysis (EDA)
- Insight generation
- Recommendation systems
- Machine learning prediction
- Model comparison and feature analysis

---

## 📊 Project 1: IMDB Top 1000 Analysis

This project explores relationships between movie ratings, popularity, and genres.

### Key Tasks
- Cleaned and standardized columns
- Converted data types
- Handled missing values
- Compared different rating and vote patterns

### Analysis
- Relationship between ratings and number of votes
- Relationship between ratings and revenue
- Distribution of votes across rating groups
- Most voted movies
- Genre popularity patterns

### Tools
- Pandas
- Matplotlib
- Seaborn

---

## 🎯 Project 2: Rule-Based Movie Recommendation System

This project builds a rule-based movie recommender using movie metadata.

### Approach
- Created a recommendation score using IMDB rating and number of votes
- Combined multiple genre columns into a structured genre representation
- Built recommendation functions based on genre filters and similarity rules

### Features Used
- Genre
- Subgenre
- Subgenre 1
- IMDB Rating
- Number of Votes

### Output
- Recommends movies based on genre preferences
- Recommends similar movies using genre overlap and ranking logic

### Tools
- Pandas
- NumPy

---

## 🤖 Project 3: ML Movie Recommendation System

This project builds a content-based movie recommender using TF-IDF and cosine similarity.

### Approach
- Combined movie metadata into a single text representation
- Applied TF-IDF vectorization
- Computed cosine similarity between movies
- Ranked the most similar movies to generate recommendations

### Features Used
- Genre
- Subgenre
- Subgenre 1
- Director
- Star1
- Star2
- Star3
- Star4
- Certificate

### Output
- Recommends similar movies based on a given movie title
- Includes title search support for easier matching

### Tools
- Pandas
- Scikit-learn (TF-IDF, cosine similarity)

---

## 📈 Project 4: Movie Rating Predictor v1 (Machine Learning)

This project builds a classification model to predict whether a movie is highly rated.

### Objective
Predict high-rated movies using numerical features.

### Features Used
- Runtime
- Meta_score
- Number of Votes

### Methodology
1. Created a binary target variable (`high_rating`)
2. Selected relevant features
3. Handled missing values
4. Split data into training and testing sets
5. Trained a Logistic Regression model
6. Evaluated model performance using accuracy

### Results
- Model accuracy: ~65%
- Baseline accuracy: ~54%

### Key Insights
- Meta_score is the strongest predictor of high-rated movies
- Runtime has a small positive effect
- Number of votes has minimal impact

### Conclusion
This project demonstrates a basic machine learning workflow and serves as a foundation for more advanced modeling.

---

## 🚀 Project 5: Movie Rating Predictor v2 (Model Comparison & Feature Engineering)

This project improves the previous model by adding richer features and comparing multiple machine learning algorithms.

### Objective
Classify whether a movie is highly rated (IMDb rating ≥ 7) using both numerical and categorical features.

### Features Used
- Runtime
- Meta_score
- Number of Votes
- Release Year
- Genre
- Certificate
- Director
- Main Actor (Star1)

### Improvements Over v1
- Added categorical features (genre, director, actors)
- Applied one-hot encoding
- Built a full ML pipeline
- Compared multiple models instead of using one

### Models Used
- Logistic Regression (baseline)
- Decision Tree
- Random Forest

### Evaluation
- Compared models using accuracy
- Analyzed classification metrics (precision, recall, F1-score)
- Used confusion matrix for deeper understanding

### Key Insights
- Random Forest achieved the best performance
- Logistic Regression provided a strong and interpretable baseline
- Decision Tree showed signs of overfitting
- Number of votes and metascore were among the most important features

### Conclusion
This project demonstrates a more advanced machine learning workflow, including feature engineering, model comparison, and interpretation. It highlights the importance of both data quality and model selection in improving performance.

---

## 📚 Learning Progression

This repository follows a structured learning path:

1. Data Cleaning & Exploration  
2. Data Analysis & Insights  
3. Rule-Based Recommendation Systems  
4. ML-Based Recommendation Systems  
5. Machine Learning Prediction (v1)  
6. Model Improvement & Comparison (v2)  

---

## 🔮 Future Improvements

- Tune model hyperparameters (Random Forest, Decision Tree)
- Reduce high-cardinality features (group rare directors/actors)
- Apply cross-validation
- Try regression models (predict exact rating)
- Use a dataset with a wider range of ratings
- Build an interactive app using Streamlit or Flask

---

## 🧰 Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📌 Summary

This repository demonstrates practical experience in:

- Data cleaning and preprocessing  
- Exploratory data analysis (EDA)  
- Feature engineering  
- Rule-based recommendation systems  
- ML-based recommendation systems  
- Supervised machine learning  
- Model comparison and evaluation  
- Interpreting model results  

It reflects a clear progression from basic data analysis to more advanced machine learning techniques.

r
