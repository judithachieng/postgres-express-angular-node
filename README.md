# TODO API 

A simple REST API with Node, Express and Postgres (using Sequelize)
## Installation

Clone this repo:

```
$ git clone git@github.com:judithachieng/postgres-express-node.git
```

Navigate to the `postgres-express-node` directory:

```
$ cd postgres-express-node
```

Install the required dependencies:

```
$ npm install
```
To run the app:

```
$ npm start:dev
```
#### ENDPOINTS

The following endpoints are provided 

|URL Endpoint| HTTP Methods | Summary |
| -------- | ------------- | --------- |
| `api/todos/` | `POST` | Create a new todo|
| `api/todos/` | `GET` | Retrieve all todos ||
| `api/todos/:todoId` | `GET` |  Retrieve one todo |
| `api/todos/:todoId` | `PUT` | Update a single todo |
| `api/todos/:todoId` | `DELETE` | Delete a todo |
| `api/todos/:todoId/items` | `POST` |  Create items in a todo |
| `api/todos/:todoId/items/:todoItemId` | `DELETE`| Delete a todo item|
| `api/todos/:todoItemId/items/:todoItemId` | `PUT`| update a todo item details|
