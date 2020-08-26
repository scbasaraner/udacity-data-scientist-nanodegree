
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Anaconda/Python 3.7 has been used and better to check necessary libraries to run the code here beyond the Anaconda distribution of Python. Package requirements for this project are below:
* numpy
* pandas
* matplotlib
* seaborn
* plotly
* scikit-learn

## Project Motivation<a name="motivation"></a>

This project is to first steps to the data science. I tried to explonotory analysis and gain some insight from Boston AirBnb Date. I try to answer three questions:

1. **Demand by Property Types:** Observing property type preferences and supply-demand gap for them.
1. **Which amenities are crucial for ratings? :** Understanding of most important amenities given by hosts.
1. **Can we predict review_score with some of the features? (Forecasts):** Trials to build a simple linear model to predict review score of houses.


#q1which amenitites has higher potantial trough rating 
#q2average weekly price based on poperty type(which is the highest) on neighbourhood_cleansed(which neighbourhood has the most price) & top 5 neighbors with their amenitites
#q3review_score precition 

## File Descriptions <a name="files"></a>

* **Data:** *listing.csv* has a list of all places in Seattle and detailed information. *Reviews.csv* includes comments that customers made. *Calendar.csv* show the availability and price of all places for one-year.

* **Code** There are 3 notebooks available here to showcase work related to the above questions.  Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There is an additional `.py` file that runs the necessary code to obtain the final model used to predict salary.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@scb/how-do-you-become-a-developer-5ef1c1c68711).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Airbnb for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/airbnb/boston/data). 

Also I would like to thanks to Udacity for Data Science Course.

Please warn me about my mistakes or do not hesitate to give inspiring ideas.
