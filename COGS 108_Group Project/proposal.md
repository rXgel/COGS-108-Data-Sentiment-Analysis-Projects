# Name and ID
Name: Rita Wan  
Github Username: ritawan

Name: Yichen Huang  
Github Username: yhuang0701

Name: Hong Tang  
Github Username: h5tang

Name: Angie Long  
Github Username: angie-long

Name: Chaolun Cai  
Github Username: rXgel

# Research Question

In the last 50 yrs of movie industry, how has the genre of most popular movie changed in the top 100 of our database in every 5 years? To be more specific, is there any correlations between the genre of each most popular movie in a particular year, 10 years later and 30 years later respectively? Furthermore, based on this trend, we hope to predict the trend of mainstream movie genre in 5, 10 and 20 years respectively from now on.

# Background and Prior work

The entertainment industry has changed over the past 50 years and the SET (Social, economic, technological)  factors have played a significant role in this trend. Socially, movies are more accessible for common people and has become one of the most common entertainment. Economically, with the economic growth, people are more likely to go to the movie theatre and spare movies on movie tickets. Lastly, the advancement in technology, there’s an increase in the number of action and sci-fi movies made in the past 50 years. According to the research (Digg), a visualization of film genre popularity has shown that there’s an increasing trend in thriller and sci-fi movies, and people seemed to have revoked their interest in musicals. Moreover, one research paper, written by Xinri Fu and Xiaoyue Yao, provides sufficient data analysis about genre shifting trends in the movie industry using data from box office revenue, academic award, investment, and etc in different genre elements over a 16 years period, which shows a correlation between each most popular genre in a particular time period and years after. This data analysis report implies that it is possible to predict the trend of mainstream movies. 


### References (include links):

- 1)https://digg.com/2019/movie-genre-popularity-1910-to-2018-data

- 2)https://www.diva-portal.org/smash/get/diva2:352538/FULLTEXT01.pdf



# Hypothesis

There is a strong correlation between the genre of the most popular movie awarded in a year and the one awarded 5 years after, then this correlation tends to be weaker as the year interval between two most popular movie awarded expands.

H0(null): There’s no obvious correlation between the genre of most popular movie awarded in different years, no matter how long of their interval. 

H1(Alternative): The correlation exists obviously between the genre of two most popular movies awarded in different years, which their maximal interval is 10. (t <= 10), then the correlation tends to be weaker as the longer the year interval will be (t>10). Hence we can make a rough prediction on the trend of mainstream movie genre in at most 20 years.



# Data
Dataset Name: The Movies Dataset
Link to the dataset: https://www.kaggle.com/rounakbanik/the-movies-dataset

Number of observations: 45,000 (movies)
This dataset contains 45,000 movies before July 2017. We plan to use this dataset to find the relationship between ratings and movie types to tackle our research questions.
 
Dataset Name: TMDB 5000 Dataset
Link to the dataset: https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

Number of observations: 5,000 (movies)
This dataset contains release date, popularity, and average rating information. We plan to use this dataset in order to verify our hypothesis by comparing the popularities/average ratings in every 5 years.


# Ethics & Privacy

The data we use are *The Movie Dataset* from kaggle and *TMBD 5000 dataset*. Both datasets are public dataset and open to anyone to use. They give permission for scientific purpose. All data are anonymous. Each user is assigned a random id and only ratings and keywords are recorded. Thus, there's no any sort of privacy violation regarding using the data and data cleaning is not needed.

The *The Movie Dataset* is updated 2 years ago, so to avoid inconsistency, the analysis will be focus on movies before 2017. As the data include IMDB and TMDB, two most popular movie dataset that contain most of the movies, we assume there's none or minimum selection bias. One potential bias is that for the older movies, the number of ratings is less than the later ones. Also, the population who rate on the internet is much smaller a few decades ago, which can potentially skew the ratings. 

We haven't identified any other issues related to the topic. If potential issues appear during analysis, we'll address them in terms of data privacy and equitable impact.

# Team Expectations

1. We hope to extract every single useful date from the database found in Kaggle and other repos, try to do our best to reduce potential bias and confounds that might occur in our experiment to conserve the internal validity of our experiment as vigorous as we can.
2. We would love to expect our lab result tends to the alternative hypothesis, instead of the null, so that we could roughly make predictions to the future popular movie trend.
3. Insert a certain amount of visualized data chart with annotations (maybe not all), so that audience can interpret more efficiently. A line graph should be included as the most succinct type of chart for predicting the trend of movie genre.

# Timeline
Week 1: This document is released  
Week 2-3: Groups are formed; Topic decided; Project Proposal Due  
Week 4-6: You have met in a group at least twice and have begun EDA.  
Week 7-8: Analysis should be underway  
Week 9: Analysis is mostly complete; group has met ~3-4 times  
Week 10: Project being edited; small improvements being made; Time is provided to work on projects in sections.  
Finals Week: Due Date for all projects and team evaluations. Submit final Jupyter notebook on GitHub.