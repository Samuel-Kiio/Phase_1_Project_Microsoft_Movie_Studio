![title](director_shot.jpeg)
# Phase 1 Project: Microsoft Movie Studio
## OVERVIEW

The project seeks to give actionable insights to Microsoft who have decided to create a new movie studio but do not know anything about creating movies. This is done after exploring what types of movies do the best at the Box Office using datasets taken from IMDB SQLite database, Box Office Mojo, The Movie database and The Numbers Database.
Data exploration and analysis methods were used to obtain this data. The results showewd that most profits come from a global audience, The United States is the most popular county by number of movies consumed and that there is no correlation between movie run time and movie popularity. The project recommends that the average movie run time be an average of 105 minutes, which is the average run-time of the top 10 movies, that despite the United states being the most popular country, Microsoft should also invest in movies that are in other languages as Norwegian is the most popular original language and that they should put more resourses in the global market.
## BUSINESS PROBLEM

Microsoft sees all the big companies creating original video content and they want to get in on the fun. 
They have decided to create a new movie studio, but they don’t know anything about creating movies. 
This project seeks to explore what types of films are currently doing the best at the box office and translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.
Given that the Microsoft don't know anything about creating movies, this project describes the factors to consider when creating new movies. It uses the data available to describe the relationship between popularity/rating of movies, which demonstrates the consumer's preference, compared to attributes of these movies including their run time, genre, language and financial resources invested in them (budgets)
## Data Understanding

The data is taken from different locations and includes data from:
1. IMDB which is located in a SQLite database. Certain characteristics such as language, run-time, attribues and ratings are described in this dataset. The tables used in this dataset are the movie_basics table, the movie_ratings table and the movie_akas table. 
2. The Movie DB shows the genre, language and popularity of a set of 26,516 movies
3. The numbers dataset describes production budget and is used to compare the profitability of domestic vs worldide markets
### 1. Looking at the most popular regions based on the number of movies in the dataset.
* Information on the most popular regions is important as it will enable microsoft to know what regions to focus on in their movie production business.
* The movie_akas table in the IMDB SQL database was used to find the top 5 regions with the highest number of movies 
![popular_regions](https://github.com/Samuel-Kiio/Phase_1_Project_Microsoft_Movie_Studio/blob/main/Most_popular_regions.png)
### 2. Looking at the relationship between movie run-time in minutes and movie ratings
* This relationship seeks to find out whether viewers rate movies with either higher or lower movie run time highly.
* It seeks to find any correlation between the highly ranked movies and their run time.
* This information can be very useful to microsoft as it will help them know whether viewers prefer long movies or short movies.
* The correlation was investigated by plotting a scatter plot of run time in minutes vs average rating
![run_time](https://github.com/Samuel-Kiio/Phase_1_Project_Microsoft_Movie_Studio/blob/main/Relationship_Between_runtime_in_minutes_and_rating-given.png)
### 3. Investigating whether the worldwide market is more profitable compared to the domestic market
* The Numbers Database was used for this analysis.
* Domestic profits and worldwide profits were calculated and two columns added to show the profits.
* A third column was added that compares the two values and determines which is greater, the domestic profits or the worldwide profits.
This investigation can be used to determine the focus on marketing and sales between the domestic or the global market.
![profits](https://github.com/Samuel-Kiio/Phase_1_Project_Microsoft_Movie_Studio/blob/main/pie_chart.png)
## Conclusion
* The conclusion is that the United States is the most popular region with 66.8% of all the movies.
* The data showed correlation between movie run - time and the popularity of a movie.
* The worldwide market is more profitable than the domestic market.
* The most popular original movie language is norwegian.
