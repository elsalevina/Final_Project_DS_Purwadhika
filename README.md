### Data Science Final Project at Purwadhika
# Netflix Movies & TV Shows Recommendation 📽️🍿

## __I. Introduction__

__Netflix__ is subscription-based streaming service which offers online streaming of a wide variety of movies and television programs, including those produced in-house. According to Wikipedia, as of April 2020, Netflix had over 182 million paid subscriptions worldwide. It seems that Neflix's popularity are increasing day by day especially on this 'stay-at-home' situation. Therefore I thought it would be interesting to do some analysis on Netflix's contents as well as to build a content-based movies & TV shows recommendation system.

#### __About the Dataset__

In this project I'm using __Netflix Movies and TV Shows__ dataset from https://www.kaggle.com/shivamb/netflix-shows.

This dataset consists of TV Shows and Movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. This dataset has 12 columns as describe below:

- __show_id__ = Unique ID for every Movie / Tv Show
- __type__ = Identifier - A Movie or TV Show
- __title__ = Title of the Movie / Tv Show
- __director__ = Director of the Movie
- __cast__ = Actors involved in the Movie / TV Show
- __country__ = Country where the Movie / TV Show was produced
- __date_added__ = Date it was added on Netflix
- __release_year__ = Actual Release year of the Movie / TV Show
- __rating__ = TV Rating of the Movie / TV Show
- __duration__ = Total Duration - in minutes or number of seasons
- __listed_in__ = Genre of the Movie / TV Show
- __description__ = The summary description

#### __Tasks:__

1. Find out what contents are available on Netflix
2. Making a simple content-based recommendation system by matching text-based features to identify similar movies / TV shows
