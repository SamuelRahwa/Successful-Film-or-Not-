# What Factors Make Films Successful?

**Author**: Samuel Rahwa

March 5, 2021

## Overview

I have been charged with putting together a report that allows Microsoft Studios to make informed decisions about creating original video content. 


## Business Problem

No one factor can make a film successful. Factors like genres, reviews, directors and star power can aid in making a film successful.

***
Business Questions:
* What genres profit the most?
* What reviews are most important?
* Who should we consider hiring to direct our films?
* Who should we consider to star in our films?
***

## Data

Two Datasets were used:

* Rotten Tomatoes 

    * Various types of Reviews, Directors and Actors/Actresses

    * 1129887 Rows

    * 28 Columns

* IMDB 

    * Genres, Budget and Grossing Data

    * 2097 Rows 
    
    * 22 Columns


## Methods

* Data Exploration
* Data Cleaning
* Creating subset dataframes for value
** To answer business questions
* Creating Visualizations to show findings



## Results


#### Top Profits By Genre:

Domestic: 
* (1) Comedy
* (2) Adventure
* (3) Action

Abroad:
* (1) Action
* (2) Adventure
* (3) Drama 

![graph1](https://github.com/SamuelRahwa/what_factors_make_a_successful_film/blob/main/images/How%20Primary%20Genres%20Generate%20Profit%2C%20Domestically%20vs%20Abroad.png)

#### Audience Ratings are the most dominate type of review, for almost every genre. 

![graph2](https://github.com/SamuelRahwa/what_factors_make_a_successful_film/blob/main/images/Which%20Review%20Types%20are%20Most%20Prevalent.png)


#### Multi-Film Directors have issues with runtime and what the audience loves to watch.
(The criteria was a minimum  production of at least 18 films)

![graph3](https://github.com/SamuelRahwa/what_factors_make_a_successful_film/blob/main/images/Multifilm%20Directors%20we%20could%20Acquire%20with%20the%20Highest%20Audience%20Rating%22.png)


#### Audience ratings pointed to multi-film Actors/Actresses were dominated by men, who mainly starred in Action, Adventure and Drama genres.
(The criteria was a minimum of being in at least 25 films)

![graph4](https://github.com/SamuelRahwa/what_factors_make_a_successful_film/blob/main/images/Multifilm%20Actors%20or%20Actresses%20we%20could%20Acquire%20with%20the%20Highest%20Audience%20Rating.png)


## Conclusions

By using the following factors: genres that profit the most, audience reviews, highest audience approvals for directors and multifilm actors/actresses to target for our original video content, we can build a successful launch point for our production studio's strategy.


## For More Information

Please review our full analysis in [our Jupyter Notebook](https://github.com/SamuelRahwa/what_factors_make_a_successful_film/blob/main/what_factors_make_a_film_successful.ipynb) or our [presentation](https://github.com/SamuelRahwa/what_factors_make_a_successful_film/blob/main/what_factors_make_films_successful_presentation.pdf).

For any additional questions, please contact **Samuel Rahwa at samuelaaronrahwa@gmail.com**

## Repository Structure


```
├── README.md                                                   <- The top-level README for reviewers of this project
├── what_factors_make_a_film_successful.ipynb                   <- Narrative documentation of analysis in Jupyter notebook
├── what_factors_make_films_successful_presentation.pdf         <- PDF version of project presentation
├── data                                                        <- Both sourced externally and generated from code
└── images                                                      <- Both sourced externally and generated from code
```
