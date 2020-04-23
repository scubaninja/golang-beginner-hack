# Bookdata-api Challenge 4

Most of the time we will be using Go in Docker, so let's write a Dockerfile for this API.

Go build produces a single binary, so this is super simple to put into a container. There no .NET framework, no Java virtual machine. All this means the container size can be super small, allowing for rapid deployment

## Task

Generate a Dockerfile for your API. The Docker image should contain only what is required to run the application.

## Hints

* [Dockerfile best practices](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)

## Success criteria

* The Dockerfile runs the API service and can be queried with Postman
* The Docker image is as lean as possible, e.g. no compilation tools

How small can you make your image? <200MB? <100MB? <50MB?? <10MB?? (Yes, it can be done).
What are the advantages and disadvantages of optimising to this extent?

If you've completed this, then [Congratulations!](congratulations.md)
