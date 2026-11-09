# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small REST API with FastAPI that lets clients view and manage tasks. Practice defining routes, validating request data with Pydantic models, and returning appropriate HTTP responses.

## 📝 Tasks

### 🛠️ Create the FastAPI application

#### Description
Create a FastAPI application for managing a task list, and add an endpoint that lets a client retrieve all tasks.

#### Requirements
Completed program should:

- Create a FastAPI application that can be run with Uvicorn.
- Store tasks in an in-memory list; each task should have an integer ID, a title, and a completion status.
- Provide a `GET /tasks` endpoint that returns all tasks as JSON.
- Confirm the endpoint works using the interactive API documentation at `/docs`.


### 🛠️ Add and retrieve individual tasks

#### Description
Let clients add new tasks and retrieve a task by its ID. Use a Pydantic model to validate task data sent to the API.

#### Requirements
Completed program should:

- Define a Pydantic model for the data required to create a task.
- Provide a `POST /tasks` endpoint that validates the request body and adds a task with a unique ID.
- Provide a `GET /tasks/{task_id}` endpoint that returns the matching task.
- Return an HTTP 404 response when the requested task ID does not exist.


### 🛠️ Update and delete tasks

#### Description
Complete the task API by letting clients update a task's completion status and remove tasks they no longer need.

#### Requirements
Completed program should:

- Provide a `PUT /tasks/{task_id}` endpoint that updates the task's completion status.
- Provide a `DELETE /tasks/{task_id}` endpoint that removes the matching task.
- Return an HTTP 404 response when an update or delete request uses an unknown task ID.
- Test successful and not-found responses for each endpoint using `/docs`.
