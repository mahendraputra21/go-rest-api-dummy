# Build a RESTful JSON API with GOlang
In this repository, we are creating an API that will allow users to create and view events using http method.

## Prerequisites
* Have Go installed. If not, check it out [here](https://golang.org/doc/install)
* Also after installing, make sure you are working inside your GOPATH

## How to run 
* clone this repository first
* run this command ```go run main.go```
* run postman ```http://localhost:8080/```

## Results in Postman
* Home Link
![Screenshot](https://github.com/mahendraputra21/go-rest-api/blob/main/images/home-link.png)

* Create Event (POST)
![Screenshot](https://github.com/mahendraputra21/go-rest-api/blob/main/images/create-event.png)

* Update Event (PATCH)
![Screenshot](https://github.com/mahendraputra21/go-rest-api/blob/main/images/update-event.png)

* Delete Event (DELETE)
![Screenshot](https://github.com/mahendraputra21/go-rest-api/blob/main/images/delete-event.png)

* Get One Event (GET)
![Screenshot](https://github.com/mahendraputra21/go-rest-api/blob/main/images/delete-event.png)

* Get All Event (GET)
![Screenshot](https://github.com/mahendraputra21/go-rest-api/blob/main/images/get-all-event.png)

# References
* https://github.com/gorilla/mux
* https://tutorialedge.net/golang/creating-restful-api-with-golang/
* https://pkg.go.dev/encoding/json
* https://pkg.go.dev/io/ioutil
* https://pkg.go.dev/net/http
* https://pkg.go.dev/log
