# Go API Server for openapi

* All endpoint paths start with a version like `/v1`
  * All versions must be maintained and functional forever or until decision is made to decommission a version
* _`POST`_ and _`PUT`_ request **payloads are JSON**
* Where possible HTTP request **status codes are used to describe the successfulness** of the requests, and content describes the details of the status
<h1>Flow states</h1> <a href=\"https://viewer.diagrams.net/?highlight=0000ff&edit=_blank&layers=1&nav=1#G1cb9foqv8zgGVY0KWIQRTiE0-21ST3WUI\">Link to Diagram</a>


## Overview
This server was generated by the [openapi-generator]
(https://openapi-generator.tech) project.
By using the [OpenAPI-Spec](https://github.com/OAI/OpenAPI-Specification) from a remote server, you can easily generate a server stub.  
-

To see how to make this your own, look here:

[README](https://openapi-generator.tech)

- API version: 0.0.1
- Build date: 2020-10-20T17:34:54.999645+02:00[Europe/Stockholm]


### Running the server
To run the server, follow these simple steps:

```
go run main.go
```

To run the server in a docker container
```
docker build --network=host -t openapi .
```

Once image is built use
```
docker run --rm -it openapi 
```


