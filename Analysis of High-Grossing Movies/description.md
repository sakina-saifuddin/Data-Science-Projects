# Analysis of High Grossing Movies
This project uses a dataset of the highest-grossing movies to analyze box office performance based on features such as rank, title, producing studio, total gross revenue, and year of release. A regression and ranking analysis is applied to examine these factors and identify patterns in movie success.
## Dataset Information
The dataset used in this project provides information about the highest-grossing movies. It includes the following columns:

| Variable | Description |
| --- | --- |
|Rank | A position of each movie based on its gross earnings |
|Title | Contains the name of the movie. |
|Studio | Lists the studio responsible for producing the movie.. |
|Gross | Total earnings of the movie at the box office, displayed in millions of dollars. |
|Year | Release year of the movie.|

## Objective
The objective of this dataset is to analyze the movies that have earned the most at the box office. It aims to identify trends in the film industry, such as the popularity of certain studios, years with higher earnings, and the impact of movie franchises on revenue.

## Approach
- Data Collection: Load the highest-grossing movies dataset with rank, title, studio, gross, and year.
- Data Cleaning: Handle missing values and encode categorical variables like Studio.
- Feature Selection: Use Rank, Studio, and Year as input features and Gross as the target.
- Model Training: Train a regression model to predict box office earnings.
- Evaluation: Measure performance using metrics like R² and mean squared error, and analyze trends such as top studios and high-earning years.

## Impact
This project helps identify trends in the film industry, such as which studios consistently produce top-grossing movies, which years see higher box office earnings, and how factors like movie rank and release timing influence revenue. It can guide studios, producers, and analysts in making data-driven decisions for future film production and marketing strategies.
