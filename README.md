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

## Limitations
1. When dealing with missing data, about 2000 rows of data are removed, which may lose some information
2. some other features may be helpful such as the the information about the main actors (the number of likes in Tweeter)
3. for the company feature, there are some different names for same company, which may make information not captured very accurately. for example, '20th Century Fox Film company','Twentieth Century Fox Film company', and '20th Century Fox' etc.
