# Data Sourcing via NYT & TMDB API's

## About

**Data Sourcing via NYT & TMDB API's** is a jupyter notebook used to query the articles search on the New York Times API as well as The Movie Database API's to retrieve data.  First we build the query URL using the provided documentation from the NYT https://developer.nytimes.com/docs/articlesearch-product/1/overview as well as the documentation from https://developer.themoviedb.org/docs/getting-started.  


## Key Features
- Implementing timers to not overload API requests
- Try and except clauses for API responses
- Formatting json into tables with pandas
- Remnoving unicode characters with lambda functions
- Modeling NYT API data to then query TMDB API
- Merging dataframes from 2 different API sources
- Exporting merged data to .csv

## Installation
Data Sourcing via NYT & TMDB API's requires the following dependencies
- Install [Python](https://www.python.org/)
- Install [Anaconda](https://www.anaconda.com/download )
- Clone this repo:  
```

git clone https://github.com/dannygallardo/data-sourcing-challenge.git

```
- Navigate to the project directory:  
```

cd retrieve_movie_data.ipynb

```
- Run Jupyter notebook
```

type jupyter notebook into command line

```

## References
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.






