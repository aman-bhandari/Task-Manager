# Task Manager With NodeJs
Task manager with Nodejs, Express and MongoDB.


## Project Setup

In order to run the project, setup .env and set MONGO_URI variable equal to DB connection string.

In order to avoid port collisions, in the source code port value is 3000





## REST API

| **HTTP Method**  | **Route**  | **Result**  |
| :------------: | :------------: | :------------: |
|  GET |  api/v1/tasks |  Get all tasks |
|  POST |  api/v1/tasks |  Create task |
| GET  |  api/v1/tasks/:id |  Get task |
|  PATCH |  api/v1/tasks/:id |  Update task |
|  DELETE |  api/v1/tasks/:id |  Delete task |



