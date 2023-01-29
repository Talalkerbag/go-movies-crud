# go-movies-crud
Run main.go file in your local machine
  Through an IDE or a terminal
Navigate to postman and try out the following to GET, POST, DELETE or UPDATE a movie from the movie struct that is in memory (no database)

(GET) http://localhost:8000/movies -> to get all movies in the hard coded movie struct object
_______________________________________ 
(POST) http://localhost:8000/movies -> will post the following movie object to the hard coded movie struct object

With the following json Body 
{
    "isbn": "00001",
    "title": "movie 3",
    "director": {
        "firstname" : "talal",
        "lastname": "kerbag"
    }
}
_______________________________________
(DELETE) http://localhost:8000/movies/1 -> will delete the movie with id "1" in the hard coded movie struct object
_______________________________________
(PUT) http://localhost:8000/movies/1 -> will update the movie with id "1" in the hard coded movie struct object with the following movie object
 {
        "isbn": "00001",
        "title": "movie 3",
        "director": {
            "firstname": "john",
            "lastname": "doe"
        }
    }
