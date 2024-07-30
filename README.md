# Go Web Application

This is a simple website written in Golang. It uses the `net/http` package to serve HTTP requests.

## Running the server

To run the server, execute the following command:

```bash
go run main.go
```


go build -o main .
./main

The server will start on port 8080. You can access it by navigating to `http://localhost:8080/courses` in your web browser.

## Looks like this
```bash

docker build . -t shubhangi045/go-web-app:latest
docker run -p 8080:8080 -it shubhangi045/go-web-app:latest
docker push shubhangi045/go-web-app:latest
```


