# tmdb-movie
Exploratory data analysis on TMBD movie data

## Introduction
1. This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. 
2. Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
3. There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is.
4. The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

## Questions:
1. Which genres are more popular and profitable
2. Which company make the most profit
3. What keywords are the most popular
4. Which movies are the most popular or profitable
5. The correlation between features

## Procedure
1. Performed data cleaning(remove NaN values and non relevant features)
2. Transformed some features like 'genre' which have multiple values for single record into single value per record
3. Conducted visualization to explore data

