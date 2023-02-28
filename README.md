## Microservice architecture for a book store using Flask, Docker and Python.
### There are 4 different services that are lightweight, independently deployable, testable and managed.

### <u> Services </u>

### 1. User

user authentication, login, logout

##### Endpoints 

- /api/user/all - GET 
- /api/user/create - POST
- /api/user/login  - POST
- /api/user/logout  - POST
- /api/user/`<username>`/exists  - GET
- /api/user/  - GET

### 2. Book

Keeps track of all the books we have in the store. 

##### Endpoints

/api/book/all - GET
- Returns all books

/api/book/create - POST
- Creates a new book

/api/book/`<slug>` - GET
- Returns book matching the slug


### 3. Order

Takes care of the ordering part

##### Endpoints

/api/order/ - GET
- Gets open orders for currently logged in user

/api/order/all  - GET
- Returns all orders

/api/order/add-item  - POST
- adds book to existing order (creates a new order if none exist)

/api/order/checkout  - POST
- marks open orders as closed

### 4. Frontend

End user interfaces with this service