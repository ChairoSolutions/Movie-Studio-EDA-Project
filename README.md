### Movie Studio Market Analysis
## Stakeholder

## Head of the New Movie Studio

## Executive Summary (For Decision-Makers)

#### Genre selection is the strongest driver of box office success, with Sci-Fi, Animation, and Adventure consistently generating the highest average revenues.

#### Ratings and runtime have limited predictive power; higher critic or audience scores and longer films do not reliably translate into higher box office returns.

#### The movie industry shows long-term revenue growth despite short-term volatility, supporting sustained investment with flexible release strategies.

### Problem Statement

#### Our company is launching a new movie studio and must determine which types of films to produce in order to maximize box office success. Currently, the company lacks historical insight into which movie characteristics most strongly influence financial performance. This analysis uses historical movie data to inform strategic production decisions.

## Business Understanding

#### This project addresses four key strategic questions:

#### Which movie genres generate the highest revenue?
 1. Identifying high-performing genres allows the 2.studio to prioritize investments with the greatest financial return.

2. Do movie ratings or critic scores affect box office performance?
Ratings from Rotten Tomatoes and IMDb are analyzed to determine whether higher scores correlate with higher revenue.

3. Does movie runtime influence ratings or revenue?
Runtime analysis helps assess whether film length meaningfully impacts audience reception or earnings.

4. Does release timing affect earnings?
Revenue trends by release month are examined to identify optimal release windows.

### Data Understanding

Three datasets were used in this analysis:

1. bom.csv.gz – Box office revenue data

2. imdb.db – Movie genres, runtimes, and ratings

3. tmdb.csv.gz – Release dates and timing

#### Initial exploration focused on identifying missing values, duplicates, outliers, and relevant columns required for analysis. These datasets form the foundation for all exploratory data analysis (EDA) and visualizations.

## Data Preparation

### Data cleaning involved:

#### Merging the three datasets into a single analytical table

#### Filtering to retain only relevant columns

#### Removing rows with null values

#### Saving the cleaned dataset to
data/processed/movie_clean.csv
to ensure reproducibility

#### Evaluation & Visual Analysis

1. Plot A: Average Box Office Revenue by Release Year
![PLOT A](Data/Images/Average Box Office Revenue by Release Year.png)

2. Plot B: Average Movie Rating by Runtime
![PLOT B](Data/Images/Average Movie Rating by Runtime.png)

3. Plot C: Movie Duration vs IMDb Rating
![PLOT C](Data/Images/Movie Duration vs IMDB Rating.png)

4. Plot D: Top Genres by Average Box Office Revenue
![PLOT D](Data/Images/Top Genres by Average Box Office Revenue.png)

5. Plot E: Movie Runtime vs Box Office Revenue
![PLOT E](Data/Images/Movie Runtime vs Box Office Revenue.png)

#### Interactive Dashboard (Tableau):
https://public.tableau.com/app/profile/sylvia.mokindo/viz/Moviedashboard_17708122892160/Dashboard2?publish=yes

## Recommendations

#### Prioritize investment in Sci-Fi, Animation, and Adventure films, as these genres offer the strongest opportunity for sustained box office success.

#### Do not rely on ratings alone when making production decisions; while strong ratings slightly improve average performance, they are not reliable predictors of revenue.

#### Adopt a long-term investment strategy supported by the overall upward trend in average box office revenue, while remaining agile during short-term market downturns.

#### Avoid using runtime as a primary decision lever; longer films show only marginal and inconsistent effects on ratings and revenue. Focus instead on story quality, cast and production value.

### Notebook Run Order 

#### To reproduce this analysis, run the notebooks in the following order:

+ 01_data_cleaning.ipynb – Loads, cleans, and merges all datasets

+ 02_eda_visualization.ipynb – Performs exploratory data analysis and generates plots

+ 03_analysis_insights.ipynb – Final insights and recommendations

 main

 ## Data Setup 
 To reproduce this project
 * Download dataset - IMDB data  - BOM.CSV.gz - tmdb.csv.gz
 * Place them inside zippedData
 * Extract im.db.zip to data
   
   
