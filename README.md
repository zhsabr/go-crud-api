# go-crud-api
Simple CRUD API 
>Used github.com/gorilla/mux

# Routes

>/movies _GET_
***
    Response
    [{
        "ID": "1",
        "isbn": "34000",
        "title": "Movie #2",
        "director": {
            "firstname": "Jesse",
            "lastname": "Pinkman"
        }
     },
     {
        "ID": "1",
        "isbn": "28000",
        "title": "Movie #1",
        "director": {
            "firstname": "Walter",
            "lastname": "White"
        }
     }
    ]
***
> /movies/{id} _GET_
***
    Response
    [{
        "ID": "1",
        "isbn": "34000",
        "title": "Movie #2",
        "director": {
            "firstname": "Jesse",
            "lastname": "Pinkman"
        }
     }
    ]
***
>/movies _POST_
***
    Request body
    {
        "isbn": "44000",
        "title": "Movie #3",
        "director": {
            "firstname": "John",
            "lastname": "Doe"
        }
    }
***
>/movies/{id} _PUT_

***
    Request body
    {
        "isbn": "45085",
        "title": "Movie #3",
        "director": {
            "firstname": "John",
            "lastname": "Doe"
        }
    }
***
>/movies/{id} _DELETE_



