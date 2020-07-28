# GraphQL with Express


## Pre-requisites

$ npm install express

$ npm install express-graphql

$ npm install json-server

$ npm install graphql

$ npm install axios

## Query Statements used in Graphiql

### Get a particular data

{
  customer(id: "5") {
    name,
    email,
    age
  }
}

### Search for all data

{
  customers {
    name,
    age
  }
}

### Add new Data

mutation {
  addCustomer(name: "White Tels", email: "whitel@gmail.com", age: 37) {
    id,
    name,
    email
  }
}

### Delete a particular data

mutation {
  deleteCustomer(id: "4") {
    id
  }
}

### Update a particular data

mutation {
  editCustomer(id: "2", age: 25) {
    id,
    name
  }
}

In this project I would be using JSON SERVER to locally use a json file to get data as like from an api.

