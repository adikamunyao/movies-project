# film industry disection
## Introduction
This project was on classification analysis of types of films currently doing the best at the box office.

![fil](https://user-images.githubusercontent.com/115970348/202153515-60275e05-7450-41fc-b4c7-50b16de6466a.jpg)
###### photocredit pixabay

## Business Understanding:

### Problem
One of the most well-known genres of art, film production has millions of spectators worldwide. There are many ways that movies can be communicated to viewers as a result of the development of various films genres over time.[here](https://doi.org/10.1093/screen/16.3.6)

## Aim
This project's goal is to investigate the movie datasets from the box office, IMDB, the movie database, and the numbers in order to provide analytical responses to business questions, profitability analysis and to determine the relationships between various movie quality indicators .
h
## Objectives
I'll conduct an exploratory data analysis to try to provide answers to the following questions:
1. **Which measure of film perfomance mostly correlates with box office revenue?**
2. **What kinds of films are most frequently produced?**
3. **The most common genres?**



## Data Understanding

### Data 

The dataset for this project was compiled from several sources. There are None datasets for this project:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [The MoieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

### Data Preparation
The datasets being from differnt sources, sorting of the data took most of the part.
This sections contains all the procedures followed in getting the data analysis ready. 

#### Datasets import
loading of the csv files and converting them into pandas dataframes

#### Data Cleaning.
The first step of data cleaning comprises fixing of structural issues on the data.
Deleting the duplicates in the data. Duplicate data must be deleted because they will bias my analysis.
The merging and joining of datasets based on shared columns using inner and left join constitutes the third step in data cleansing. Drooping columns that were not part of my analysis.

### Data Preview.
These were the columns used in the final dataset.
 * release_date
 * original_title
 * production_budget
 * domestic_gross
 * worldwide_gross
 * averagerating
 * genres
 * numvotes
 * runtime_minutes
 * studio
 * domestic_profit

### Exploratory Data Analysis.
*1 Genre Analysis

*2 Runtime Analysis

*3 Pofitability analysis

### Conclusions.
* Drama, Comedy and Action are the top genres. As seen in the pie chart and wordcloud
* Production budget and domestic gross have a high correlation.
* Drama genre continues to dominate most of the movies being produced.
* Runtime of movies has not greatly changed over the yaers as seen from the analysis.
* Significant number of movies go into loss.
* Movies that audience easily relates with are popular and have higher ratings.


### Recommendations.
* To enter into the film industry, it is important to consider short movies at an average of 50 minutes.

* There are factors that affect the movie perfomance after it has been prodced these include release date and the streaming platforms.

* 
More research could be done to understand what causes movies to be non profitable. This could help avoid loss in the movie industry.

### Repository Guide.