# Bookdata-api Challenge 2

## Task

You might have noticed the CSV file in your repo, it's in the ```assets/``` directory.
Your task is to modify the API to read the book data from the CSV file, rather than using the struct literal.

This should be read once at startup, then the rest of the operations will continue in memory. The API should output how long the read takes.

## Hints

* Stick to the standard library, you shouldn't need any other imports
* Have a read of [Os.Open](https://golang.org/pkg/os/#Open) & [encoding/csv](https://golang.org/pkg/encoding/csv/) in the standard library
* [Defer](https://tour.golang.org/flowcontrol/12) is one of Go's coolest features

[If you're stuck](https://medium.com/@ankurraina/reading-a-simple-csv-in-go-36d7a269cecd)

## Success criteria

* The CSV file is read into memory
* The executable outputs how long the read took

