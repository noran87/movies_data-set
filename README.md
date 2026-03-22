# Movie Data Analysis & Machine Learning Portfolio

This repository contains a collection of projects focused on exploring movie datasets using Python, data analysis, and machine learning techniques.

The goal of this repository is to demonstrate a clear learning progression:
- Data cleaning and preparation
- Exploratory data analysis (EDA)
- Insight generation
- Recommendation systems
- Machine learning prediction


## Project 1: IMDB Top 1000 Analysis

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


## Project 2: Rule-Based Movie Recommendation System

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


## Project 3: ML Movie Recommendation System

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


## Project 4: Movie Rating Predictor (Machine Learning)

This project builds a classification model to predict whether a movie is highly rated (IMDB rating ≥ 8).

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
This project demonstrates a complete machine learning workflow, including data preparation, model training, evaluation, and interpretation.

## Learning Progression

This repository follows a structured learning path:

1. Data Cleaning & Exploration  
2. Data Analysis & Insights  
3. Rule-Based Recommendation Systems  
4. ML-Based Recommendation Systems  
5. Machine Learning Prediction  


## Future Improvements

- Experiment with advanced models (Random Forest, Decision Trees)
- Improve feature engineering
- Add more features such as genres or directors to prediction tasks
- Build an interactive app using Streamlit or Flask


## Summary

This repository demonstrates practical experience in:
- Data cleaning and analysis
- Feature engineering
- Rule-based recommendation logic
- ML-based recommendation using text similarity
- Supervised machine learning workflows
- Model evaluation and interpretation

It serves as a strong foundation for more advanced data science and machine learning projects.
