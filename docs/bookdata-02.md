# Bookdata-api Challenge 2

Now that you understand the code a little, it's time to make some improvements!

## Task

You might have noticed the CSV file in your repo, it's in the ```assets/``` directory.
Your task is to modify the API to read the book data from the CSV file, rather than using the struct literal.

This should be read once at start-up, then the rest of the operations will continue using the in-memory data. The API should output how long the read operation takes.

## Hints

* Stick to the standard library
* Have a read of [Os.Open](https://golang.org/pkg/os/#Open) & [encoding/csv](https://golang.org/pkg/encoding/csv/)
* [Defer](https://tour.golang.org/flowcontrol/12) is one of Go's coolest features

## Success criteria

* The CSV file is read into memory
* The executable outputs how long the read operations took
