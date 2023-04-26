# IMDB-clone app


<img width="1080" alt="homepage" src="https://user-images.githubusercontent.com/110377660/234664347-2cc8d86f-9112-4ea6-96ba-272601fe3bcd.png">

<img width="1075" alt="moviepage" src="https://user-images.githubusercontent.com/110377660/234664388-198b0829-b0d9-47b7-85ed-e0b633ec376c.png">

A mini IMDB clone app in which we can search movies based on OMDB API, with search suggestions like google.. 
Clicking on a particular movie card opens a new movie page for more info like cast , genre etc...
On clicking on the favourite button, we can add a movie to the favourite list which is using local storage to store movies.  

### Hosted link: https://naresh-gudipalli.github.io/IMDBclone/

## Tools used:
* HTML
* CSS
* Bootstrap
* JavaScript
* OMDB API

### Functionality
* Search movies with suggestions.
* Click on Movie card for more info.
* Add a movie to the favourites list.
* Delete movie from the favourites list.

### Data
* suggestionList - an array which contains a list of movies based on searched keywords.
* favMovieArray - an array that gets movies from the local storage. 
* movieName - local Storage item which contains the name of clicked movie card.

### Functions (in code)
* fetchMovies
* addToSuggestionContainerDOM
* handleFavBtn
* addToFavDOM
* deleteMovie
* notify
