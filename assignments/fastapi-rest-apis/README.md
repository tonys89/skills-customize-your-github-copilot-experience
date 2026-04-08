# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn to build REST APIs using the FastAPI framework in Python. This assignment covers creating endpoints, handling HTTP requests and responses, path parameters, query parameters, and basic API documentation.

## 📝 Tasks

### 🛠️ Set Up FastAPI Application

#### Description
Install FastAPI and create a basic FastAPI application with a root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn using pip
- Create a FastAPI app instance
- Define a GET endpoint at "/" that returns a JSON response with a welcome message
- Run the server and verify the endpoint works

### 🛠️ Create REST Endpoints

#### Description
Add multiple REST endpoints to the application, including GET, POST, PUT, and DELETE operations for managing a simple resource (e.g., a list of items).

#### Requirements
Completed program should:

- Create a GET endpoint to retrieve all items
- Create a POST endpoint to add a new item
- Create a PUT endpoint to update an existing item by ID
- Create a DELETE endpoint to remove an item by ID
- Use path parameters for item IDs and request bodies for item data
- Include proper status codes and error handling