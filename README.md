# Top 1000 IMDB Movies – Exploratory Data Analysis (EDA)

## Project Overview

This project explores the Top 1000 IMDB movies dataset to understand the relationships between movie ratings, audience engagement, revenue, and genres.
The goal is to practice real-world exploratory data analysis (EDA) and extract clear, honest insights from data.

## Tools Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

## Key Questions Explored

- Do higher-rated movies make more money?
- Do movies with higher IMDB ratings make more money on average?
- Do movies with more votes tend to have higher ratings?
- Do higher-rated movies receive more votes?
- Which genres are most common in the Top 1000 movies?
- Which genres receive the most audience engagement (votes)?


## Dataset

- **Source:** Kaggle – Top 1000 IMDB Movies
- **Rows:** 1000 movies
- **Key Columns:**
  - `Series_Title`
  - `Released_Year`
  - `IMDB_Rating`
  - `No_of_Votes`
  - `Gross`
  - `Genre`, `Subgenre`, `Subgenre 1`
  - `Certificate`
  - `Meta_score`


##  Data Cleaning 

- Converted `Released_Year` to numeric format.
- Filled missing categorical values (`Certificate`, `Subgenre`, `Subgenre 1`) with `"Unknown"`


## Key Highlights

### Rating vs Revenue
Higher-rated movies do not consistently make more money. The apparent higher revenue in the top-rated group is influenced by a very small number of movies, making the result unreliable.

### Rating vs Votes
- Votes and ratings have a moderate positive relationship, but votes are not the main factor driving ratings.
- There is a moderate positive relationship between rating and number of votes. Higher-rated movies generally receive more audience votes.

### Most Voted Movies
The top 5 most voted movies all have high ratings. This shows that popular movies are often highly rated as well.

### Genre Analysis
Drama is the most common genre in the Top 1000 IMDB movies, followed by genres such as Crime and Action.

### Genre and Votes
Genres such as action and mystery tend to receive the highest average number of votes.



