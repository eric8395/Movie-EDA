# An Exploratory Data Analysis on Movie Data

<p align="center">
  <img src = "https://thewell.unc.edu/wp-content/uploads/sites/1007/2020/04/film1.jpg" width="400" height="250">
</p> 

## The Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. 

What is the demographic of successful movies and how well do they do in the box office? 

The goal is to explore the types of films that are currently doing the best in the box office and translate these findings into actionable insights for Microsoft's new movie studio. 

## The Dataset

Basic movie information data was collected from the IMDB database (www.imdb.com) and contains characcteristic information pertaining to movie release dates, genres, and IMDB ratings. 

Financial movie data was collected from 'The Numbers' (www.the-numbers.com) and has a comprehensive database of movie financial data. The data files provide movie release dates, production budgets, domestic and worldwide gross for movies. 

## Methods

This project involved cleaning the datasets for relevant information pertaining to success and popularity of a movie. Descriptive analysis, including visualizations of trends over time, are produced to provide further context on what makes a movie popular. These visualizations provide overview of historical movie demographics as well as commentary on recent movie box office success that can assist Microsoft Studios in developing future profitable movies. 

## Results

<p align="center">
  <img src = "https://github.com/eric8395/Movie-EDA/blob/main/images/movieruntimedist.png" width="700" height="300">
</p> 

- Most movies are normally distributed with a runtime of 90 minutes and have an average IMDB rating of 7 out of 10. 

- Movies with greater amount of ratings, generally, have a higher IMDB rating. 

- The most frequently occuring movie genre (since the 1900s) is the 'drama'. Though, this does not indicate the most popular genre. 

<p align="center">
  <img src = "https://github.com/eric8395/Movie-EDA/blob/main/images/movieprofits_by_month.png" width="700" height="400">
</p> 
- Movies make the most money at the box office worldwide than compared to domestic box office profits. Summer and winter holiday months generate the greatest average profit. 

<p align="center">
  <img src = "https://github.com/eric8395/Movie-EDA/blob/main/images/averageprofits_since1960.png" width="750" height="400">
</p> 

- Average yearly movie profits has been cyclical since the 1960s. There has been an exponential rise in worldwide yearly movie profits in the 2010s. The 2020 Pandemic greatly impacted the movie industry where losses were made. 


<p align="center">
  <img src = "https://github.com/eric8395/Movie-EDA/blob/main/images/top20.png" width="750" height="400">
</p> 

- The top 20 most profitable movies were all released post 2010. 
  - Half of the top 20 movies are classified as a action, adventure, and sci-fi genre (ie. Avengers: Infinity War, Jurassic World, Black Panther)

## Recommendations
Microsoft Studios should look to produce films that have the following characteristics and target the following demographics:

- 90 minute movie runtimes generally yield a favorable rating of 7/10
- Produce movies that focus on action, adventure, or sci-fi. These genres produced over half of the top 20 most profitable movies. 
- Target the student or kid demographic. More people have more time during the summer and holiday seasons and are more inclined to go to a theater. More people = greater profit for the studio. 
- Market the movie worldwide. Worldwide movies generate far more in profit than when consumed domestically. 

## Next Steps
While the data we have available can help us measure previous movie information, there are some additional steps we can take to provide a more detailed analysis. 

- Continue to collect data for movies post 2020. Are we starting to see the movie and theater industry recover? Are people returning back to the theater?
- Adjust movie data for inflation. While measuring profits can be helpful, we can get a better relative sense of monetary performance in the box office when adjusting profits for inflation. 
- Collect additional data to help explain cyclical cycles in the movie industry over the years. Could there be other reasons why we see spikes in some years where movie profits were exceptionally high? 

## Repository Structure

```
├── images
├── .gitignore
├── Phase 1 Project - Movie EDA.pdf
├── Project 1 - Movie EDA.ipynb
└── README.md
```
