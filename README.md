# BOOK RECOMMENDATION SYSTEM

### Software And Tools Requirements

1. [GithubAccount](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

## Objective

The main objective is to create a book recommendation system for users. Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors.

## Methods Used

1. Descriptive Statistics
2. Data Visualization
3. Machine Learning

## Technologies
1. Python
2. Pandas
3. Numpy
4. Matplotlib
5. Seaborn
6. Scikit-learn
7. Surprise

## Data

The Book-Crossing dataset comprises 3 files.

Users : Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL values.

Books : Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon website.

Ratings : Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

## Project Description

EDA - Performed exploratory data analysis on numerical and categorical data.

Data Cleaning - Missing value imputation,Outlier Treaatment

Feature Selection - Used User-ID,ISBN and Books-Rating for model development.

Model development - Tried Popularity based model and Collaborative filtering (Both Memory based and Model based).

## Needs of this project

1. data exploration
2. data processing/cleaning
3. recommendation system developer
