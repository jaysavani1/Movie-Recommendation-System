
## Authors

- [@jaysavani1](https://www.github.com/jaysavani1)


# Project - Movie Recommendation System

Movies move us like nothing else can, whether they’re scary, funny, dramatic, romantic or anywhere in-between. So many titles, so much to experience. It becomes one of the major source of entertainment in 21st century.

This movie recommendation system provides you the recommendation of the movie based on movies you already know or like. One just needs to enter the name of your favourite movie and based on "similarity score" the system recommends you similiar movie to watch.

This system also provide the review sentiments as either movie is "Good" or "Bad". Based on that user get the idea what kind of reviews provided by other viewer of the movie.

# Where to access the project?

The basic version of this project is already live. You can visit [Click Here:- Movie-Recommendation-System.](https://movierecommendjs.herokuapp.com/)

Advanced version coming soon !!!

# Basic Architecture:
![image](https://user-images.githubusercontent.com/39219880/153902590-3140a7b7-7faf-4d83-b793-94e3b1498601.png)


# What is similarity score and how it works?

Basically, it is numerical value ranges between 0 to 1, determines on this scale that how much two items or objects similar to each other.
Here, I have used cosine similarity score which determied similarity based on text details between two or more items.

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

# Datasets

- [@ Movies Till 2016](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
- [@ Movies -2017](https://en.wikipedia.org/wiki/List_of_American_films_of_2017)
- [@ Movies -2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
- [@ Movies -2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
- [@ Movies -2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)
- [@ Movies -2021](https://en.wikipedia.org/wiki/List_of_American_films_of_2021)

## API Reference - TMDB Movie

#### API is provided by TMDB website given below.

```http
  https://www.themoviedb.org/documentation/api
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |


## How to get your own API?
- Go to website mentioned above and create a new account.
- After login to account, go to **API** section from left sidebar in account setting.
- Fill the details to get API.
- For website URL you can enter 'N/A'. (In case you don't have any).
- After approval, you can see your own personal API.
#### 

