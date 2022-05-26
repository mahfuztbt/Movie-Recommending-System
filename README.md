# The-tbtmovie 

![Python](https://img.shields.io/badge/Python-3.9-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![API](https://img.shields.io/badge/API-TMDB-fcba03)

“tbtmovie” adds a whole new dimension to the movie watching experience by providing movie recommendations to users. “tbtmovie” movie recommendation system designed specifically for Hollywood movies and it also provide to the user with the basic information about the movie and classification of movie reviews using Deep Learning. It alters the existing system using the content-based filtering approach. Similar movies are recommended using parameters such as movie title, director, top three actors, genre to find the similarity among the movies using cosine-similarity and displays it to user. Movie review classification is done by using RNN, a Deep Learning classification algorithm. Tmdbv3 API is used to gather the data from the movie database. 
This system deals with Recommendation Movies to the user, movie details and analysis reviews and classifies those reviews available in the internet. 
This application provides all the details of the requested movie such as overview, genre, release date, rating, runtime, top cast, reviews and based on user choice the system recommended movies to them, etc.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using `beautifulsoup4` and performed sentiment analysis on those reviews.

## Project Demo


https://user-images.githubusercontent.com/67628125/169972164-3a6cf882-5322-444d-9324-a1331f947610.mov



## How to get the API key?

Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

## How to run the project?

1. Clone this repository in your local system.
2. Install all the libraries mentioned in the [requirements.txt] file with the command `pip install -r requirements.txt`.
3. Replace YOUR_API_KEY in **both** the places (line no. 23 and 43) of `static/recommend.js` file.
4. Open your terminal/command prompt from your project directory and run the `main.py` file by executing the command `python main.py`.
5. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
6. Hurray! That's it.

### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)
6. [List of movies 2021](https://en.wikipedia.org/wiki/List_of_American_films_of_2021)
7. [List of movies 2022](https://en.wikipedia.org/wiki/List_of_American_films_of_2022)
.
