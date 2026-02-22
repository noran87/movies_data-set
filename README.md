# Movie Recommendation System (IMDB Top 1000)

This project builds a **content-based movie recommendation system** using the IMDB Top 1000 Movies dataset.

The goal is to recommend movies based on **genre similarity**, **movie quality**, and **audience popularity**, without using machine learning models.

## Dataset

- Source: IMDB Top 1000 Movies (Kaggle)
- Size: 1000 movies
- Key features used:
  - Genres (Genre, Subgenre, Subgenre 1)
  - IMDB Rating
  - Number of Votes
  - Release Year

The dataset was cleaned and prepared in a separate EDA notebook before building the recommendation logic.

## Recommendation Logic

Movies are recommended based on three main signals:

- **Quality** → IMDB Rating  
- **Popularity** → Number of Votes  
- **Similarity** → Genre overlap  

A custom score combines rating and vote count, and recommendations are ranked by:
1. Number of shared genres  
2. Overall recommendation score  

All similarity and ranking values are computed **dynamically** based on user input.

## Features Implemented

- Genre-based recommendations  
- Multi-genre overlap recommendations  
- Similar-movie recommendations (“If you liked this movie, try these”)  
- Minimum rating and vote thresholds  
- Helper function for partial movie title search  


## Example Usage

recommend_movies('Mystery')

recommend_by_genres(['Thriller', 'Mystery'])

find_title('fight')
recommend_similar('Fight club')


## Key Takeaways

- Recommendation systems can be built using clear, rule-based logic  
- Genre similarity improves recommendation relevance  
- Combining rating and popularity avoids niche or low-quality recommendations  
- Explainable systems are valuable even without machine learning  

## Conclusion

This project focuses on building a **transparent and explainable recommendation engine** using real-world data.
It demonstrates practical data cleaning, feature engineering, and recommendation logic design.
