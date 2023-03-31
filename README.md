# Netflix_Movies_and_TV_Shows_Clustering

Hello, all. We have worked on the Netflix Movies and TV Shows dataset provided by a third party until the year of 2019. The dataset contains information of the various TV Shows, Movies, Documentaries and many more content on the streaming service provider's website.

Title, Cast, Director, Country of Production and Description are some of the things available for each content on the streaming website.

We have tried to work on the data and get three things out of it:

a. We have tried to generate insights through the EDA process

b. We have tried to analyse the change in Netflix's operations

c. And most importantly, we have tried to build a machine learning clustering model that helps us segregate the contents based on similarity in various features.

We hope that you like the project and we would like to listen to your thoughts on it. You can reach us at shivchirag1997@gmail.com and er.tapomay@gmail.com

## Problem Statement

Netflix is a very popular online streaming service provider offering a variety of TV shows, movies, documentaries and lots more to watch. We have the dataset containing the list of their TV shows, movies and the other content that they have on their platform. The list is procured from a third party website and contains information until 2021.

We are supposed to offer insights from the dataset on Netflix and its content. We are also supposed to cluster the contents based on text features.

## Dataset

We have 7787 datapoints and 12 columns. Most of the variables are text data. Only release year is numeric, but it is also discrete in nature.

**show_id :** Unique ID for every TV show/movie

**type :** Movie or a TV Show

**title :** Title of the content

**director :** Director of the content

**cast :** Star cast of the content

**country :** Country of production

**date_added :** Date the content was added on Netflix

**release_year :** Release year of the content

**rating :** TV Rating of the content

**duration :** No. of mins (how long) in case of movies and No. of seasons in case of TV shows

**listed_in :** Genre of the content

**description :** Summary description for the content

## Data Cleaning and Wrangling

We have segregated the dataset based on the content type. We have also made the date_added column's datatype datetime. And then we extracted the month, year and day of the week as individual columns from the main column.

## EDA Process, Hypothesis Testing and Clustering

We did an extensive analyis of the dataset using charts like simple barplot, stacked barplot, grouped barplot, line plot and pie chart. These were used to do multiple univariate, bivariate and multivariate analysis and reach to the final set of insights.

We then did two hypothesis testings - one between two categorical columns and one between two continuous columns.

Finally, we made two clustering models - one using KMeans and the other using Agglomerative Hierarchical Clustering.

For more on the process and the results, would recommend to go through the project notebook uploaded and/or the final presentation prepared.
