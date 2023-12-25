# File locations to find the answers
- *Dependency injection* : \Controllers\BookController.cs
- *Extension* : \Extensions\StringExtensions.cs, \Services\BookService.cs
- *Swagger* : \Program.cs
- *Global log* : \Program.cs
- *Fake user login* : \Services\FakeAuthService.cs
- *Global exception* : \Program.cs
# Requests
## Fake User Authenticate
- [POST] https://localhost:7111/api/FakeUser/authenticate
## Book
- [GET]   https://localhost:7111/api/Book
  - get all books
- [POST] https://localhost:7111/api/Book
  - add new book 
- [GET]   https://localhost:7111/api/Book/list?order=name
  - get all books in order. Options: {"name", "id", "price", "author"}
- [GET]   https://localhost:7111/api/Book/1
  - get book by id   
- [PUT]   https://localhost:7111/api/Book/1
  - update all values of the book 
- [PATCH] https://localhost:7111/api/Book/1
  - update the specified values of the book
- [DELETE]https://localhost:7111/api/Book/1
  - delete book by id
# Swagger
![image](https://github.com/yigitbayraktaroglu/Akb-Bootcamp-Week2/assets/81326341/092e086f-47d9-4ce0-a4e4-6eba7e042bb4)

