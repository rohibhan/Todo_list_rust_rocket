# Implement a REST API using the Rust web framework Rocket. The API should allow users to create, read, update, and delete resources for a simple todo list application. The following endpoints should be implemented:

### GET /todos - Returns a list of all todos.

### GET /todos/:id - Returns a specific todo by ID.

### POST /todos - Creates a new todo.

### PUT /todos/:id - Updates an existing todo by ID.

### DELETE /todos/:id - Deletes a specific todo by ID.

---

> Each todo should have the following properties:

---
### id - A unique identifier for the todo.

### title - A brief title or summary of the todo.

### completed - A boolean value indicating whether the todo is completed or not.
---
> The API should store the todos in memory, so there's no need to use a database. The code should be well-organized and maintainable, with clear separation of concerns between the web layer and the business logic layer. The code should also include appropriate error handling and input validation.


## Usage
### To run the program default and check Todo_postman.json

```bash 
cargo run
```







