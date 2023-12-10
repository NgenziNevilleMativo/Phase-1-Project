# Microsoft Movie Recommendation System

**Author:** Neville Ngenzi

## Business Understanding

### Introduction

It is Microsoft's time to Dive deep into the world of film, decipher the trends, and emerge with the knowledge that will propel Microsoft's movie studio to stardom on their launch. The stage is set, the cameras are rolling, and the future of Microsoft's cinematic journey rests upon this insightful analysis.

### Overview

This project aims to build a robust movie recommendation system by leveraging a diverse dataset encompassing user behaviour and movie characteristics. By analyzing these data points together, we identify patterns and relationships between movies and user preferences, resulting in a recommendation system capable of accurately predicting user engagement with specific movies. Further analysis is recommended to refine the system and explore the inclusion of additional data sources, such as social media interactions and user demographics, to enhance its accuracy and personalization further.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### Objectives

#### Main Objectives.

* To demonstrate how other movie data may affect Microsoft’s movie recommendation system that will be used to leverage the data-driven insights and market trends.

#### Specific Objectives

* Optimize Film Production Strategy.

* Facilitate Informed Decision-Making for Financial Success.

## Data Understanding

This research uses data from several sources, such as box office data, movie attributes, and critical response data, to detect trends and determine what influences the performance of films. A sample of movie releases with both quantitative and categorical factors is represented by the data. To properly comprehend the data and prepare it for efficient analysis, more analysis was required.

## Data Preparation

The data that was converted and stored to  'movies_df' will be explored and analyzed. The data will make obtaining descriptive statistics and checking for duplicates easier. Data cleaning is performed to handle missing values and outliers, and to address any inconsistencies or errors. From the large dataset we will select some specific columns from the DataFrame 'movies_df' for easier descriptive analyis and determine the number of records, preview top and bottom of the merged dataset and each column's data type.

We are going to CLEAN the data by generating new variables, and employ methods for handling missing values or outliers while maintaining business decisions.

1. Removing duplicate rows from the DataFrame 'movies_df'.
2. Handling missing values.
3. Creating new features for the dataset.
4. Aggregating the data.
5. Detecting and handling outliers.

## Data Modeling

We will interpret the results of the dataset and see if the model changed significantly and to what extent would the results be of accurate data. 

1. Scatter plot showing a visual representation of the relationship between the domestic gross and foreign gross earnings of movies.
2. Analyzing the average ratings of movies by genre.
3. Bar chart showing the total gross earnings for each genre.

## Evaluation

From our viualizations above, we will be answering what our interpretations are to our findings, to what extent does our analysis align with the dataset? how certain are we about the generalizability of the results in the data and to What level of confidence do we have in the potential business impact.

1. #### Scatter plot showing a visual representation of the relationship between the domestic gross and foreign gross earnings of movies
* Some movies have a higher foreign gross compared to their domestic gross and vice versa. This indicates that the appeal of a movie can vary between domestic and international audiences. Understanding these differences can help in tailoring movies to specific markets.
* By analyzing this plot and the data, Microsoft’s new movie studio can gain insights into the types of films that are doing well both domestically and internationally.

2. #### Analyzing the average ratings of movies by genre
* This can help them make informed decisions about the kind of films they should produce. For instance, if movies of a certain genre consistently show high gross earnings both domestically and internationally, it might be a good idea for the studio to consider producing films of that genre.The genres that have the highest average ratings are probably the ones that people like watching the most. Genre-specific film production has the potential to increase audience and, in turn, revenue.
* With an understanding of viewer preferences may be gained from examining average ratings, a high average rating for a given genre indicates that viewers enjoy the films in that genre.

3. ### Bar chart showing the total gross earnings for each genre
For a movie recommendation system, examining the stacked bar chart that displays the overall gross by genre might yield various insightful findings. 
* It can first identify popular genres that ought to be given priority when making suggestions. Furthermore, a wide variety of genres that contribute to a high overall gross imply that the system should provide a wide selection to accommodate different audience tastes.
* Additionally, investigating popular genre pairings, such as "Action" and "Adventure," might help guide recommendation systems. Lastly, determining failing genres and examining seasonal patterns might assist in making well-informed choices on the content of the system.

## Conclusions

In light of this study, we are going to give recommendations on what Microsoft Movie Recommendation system would be benefitial for the company.
1. Strategic Film Production and Genre Emphasis:
* Filmmaking can be directed by the information gleaned from the analysis. The studio may decide which genres work well with audiences and produce more movies in areas where evaluations are generally positive. As a result, more popular and well-received movies are made.
2. Risk Mitigation and Diversification: 
* When assessing risks in the filmmaking process, the analysis is a useful tool. In terms of audience reaction, genres with continuously poor average ratings may carry more risks. Microsoft may use this knowledge to establish risk mitigation methods and take a careful approach to film creation in certain genres. In order to mitigate potential risks and maintain a well-rounded selection of films that appeal to a wide range of audiences while retaining a concentration on genres that have demonstrated success, the studio may also think about diversifying its portfolio.
3. Informed Decision-Making for Financial Success: 
* Microsoft will use the data-driven insights to make well-informed judgments about the sort of movies they should develop. For example, suppose films in a particular genre continuously generate big sums of money both domestically and abroad. In that case, the studio may give priority to producing more of those kinds of films, which will increase the chances of both financial success and favorable reviews from viewers.
4. Adaptation to Market Trends: 
* Microsoft will regularly track changes in the popularity of different genres over time in order to keep ahead of evolving market trends. The studio will modify its movie recommendation system to suit changing audience tastes thanks to this continuous knowledge. The ability to modify the recommendation algorithm will guarantee that the system will always be at the forefront of evolving market dynamics, offering consumers ideas for films that are appealing and relevant to their tastes and current interests.
