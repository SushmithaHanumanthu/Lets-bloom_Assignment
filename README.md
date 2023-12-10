In this code ((for-each-endpoints) from main), the Book class represents the book information and the BookRepository interface extends the JpaRepository interface. 
This interface provides CRUD methods for the Book entity. The BookController class handles HTTP requests and uses the BookRepository to interact with the d
We can enhance this code by adding proper error handling, input validation, and data mapping between the API request and the database.

Step wise explaination-
Implementations for each end-points:

1. GET /api/books: Retrieves all books from the database and returns them in the response.

2. POST /api/books: Creates a new book with the provided information and saves it in the database.

3. PUT /api/books/{id}: Updates the book with the given ID using the provided information.
