# Movie Studio Market Analysis
## Stakeholder
Head of the New Movie Studio

## Problem Statement
Our company is launching a new movie studio and needs to decide what types of films to produce in order to maximize box office success. However, the company currently lacks historical knowledge about which movie characteristics lead to strong financial performance.

## BUSINESS UNDERSTANDING

***KEY QUESTIONS FOR MOVIE STUDIO STRATEGY***

1. **Which movie genres generate the highest revenue?**  
   By analyzing the total earnings from different genres, we can determine which types of films are more profitable and more likely to attract large audiences.

2. **Does movie rating or critic score affect performance?**  
   Using ratings from Rotten Tomatoes and IMDb, we can measure whether higher-rated movies tend to earn more revenue.

3. **Does a longer runtime affect ratings or revenue?**  
   By analyzing movie runtimes, we can identify whether certain runtimes generate higher earnings or better ratings across different genres.

4. **Does release timing affect earnings?**  
   By examining release months and their associated revenues, we can identify the optimal times of the year to launch films for maximum success.

## JOINING DATA EXPLOITATION
   Using the Box Office and IMDB Datasets, We explore the data to investigate possible joins that can be used during our Analysis. The Columns (primary_title,start_year) on IMDB and (title,year) on Box Office data together, we see a successfull join using pandas hence a crucial step in Data Preparation.

## IMDB BASICS DATA CLEANING
Use the columns (Genres, Runtime and Years) on the table Movie Basics to do the data cleaning to ensure Accuracy, Consistency and Reliability by Removing errors, duplicates and inconsistencies from the dataset.