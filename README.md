# Todo List Backend Project

Welcome to the Todo List Backend Project! This project provides a backend solution for a todo list application, allowing users to efficiently manage their tasks. Users can add tasks with descriptions and deadlines, mark tasks as completed, and edit or delete tasks as needed.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

# Features

- **Task Management**: Create, read, update, and delete tasks.
- **Task Descriptions and Deadlines**: Add descriptions and deadlines to tasks for better organization.
- **Mark Tasks as Completed**: Keep track of completed tasks.
- **RESTful API**: Provides a clean and intuitive API interface for interacting with the backend.

# Technologies Used

- **Node.js**: Server-side JavaScript runtime environment.
- **Express.js**: Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB**: NoSQL database used for storing task data.
- **Mongoose**: MongoDB object modeling for Node.js.
- **Postman**: API development and testing tool for interacting with the backend API.

# Dependencies

```json
{
  "dependencies": {
   "express": "^4.17.1",
    "mongoose": "^6.0.13",
    "dotenv": "^10.0.0",
    "body-parser": "^1.19.0",
    "morgan": "^1.10.0"
  }
}
  ```

# Prerequisites
sudo apt install nodejs
sudo apt install mongodb
sudo snap install postman

# Installation
```bash
git clone https://github.com/Sourav-Sir/todo-list-backend-project.git
cd todo-list-backend-project
npm install
npm start
```
# Usage
Once the server is running, you can use Postman or any other API client to interact with the backend API. Refer to the API Endpoints section below for details on available endpoints and how to use them.

## Api Endpoints
```
- GET /tasks: Retrieve all tasks.
- POST /tasks: Create a new task.
- GET /tasks/:id: Retrieve a specific task by ID.
- PUT /tasks/:id: Update a specific task by ID.
- DELETE /tasks/:id: Delete a specific task by ID.
 ```

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request. Please follow the contributing guidelines.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
