### Order Service

Takes care of the ordering part

##### <u>Endpoints</u>

- /api/order/ - GET
  - Gets open orders for currently logged in user

- /api/order/all  - GET
  - Returns all orders

- /api/order/add-item  - POST
  - adds book to existing order (creates a new order if none exist)

- /api/order/checkout  - POST
  - marks open orders as closed