# Bookdata-api Challenge 3

You have been asked to add some features to your API :)

## Task

Add the following additional methods onto the API:

* Search by author, using a partial match on the name. E.g. ```/books/authors/rowling``` would match "J. K. Rowling"
* Search by Title/Book Name, again using a partial match. E.g. ```/books/title/harry``` would match the Harry Potter... series of books
* Search by ISBN. should only return an exact match. E.g. ```/book/isbn/{isbn}```
* Create new book. E.g. HTTP POST to ```/book``` using a form
* Delete book by ISBN. E.g. HTTP DELETE to ```/book/isbn/{isbn}```

## Hints

* net/http provides the ParseForm method on the HTTP request

## Success criteria

* Search operations succeed and are not case sensitive
* Create operations succeed and report errors when invalid form data is supplied
* Delete operations succeed and report errors when the ISBN isn't found

Next, let's look at the [bookdata-api challenge 4](bookdata-04.md)
