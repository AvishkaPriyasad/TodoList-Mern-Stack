# To-do List Application

A full-stack Todo List application built with React, Node.js, Express, and MongoDB. This application allows users to manage their tasks effectively by adding, marking as completed, and deleting tasks.

---

## Features

- **Add Tasks:** Easily add new tasks to your list.
- **Mark as Completed:** Update the status of tasks to mark them as done.
- **Delete Tasks:** Remove tasks from the list when they are no longer needed.
- **Real-Time Updates:** All updates happen dynamically without requiring a page reload.

---

## Tech Stack

### Front-End
- **React:** For building the user interface.
- **Axios:** To handle HTTP requests.

### Back-End
- **Node.js:** JavaScript runtime for server-side programming.
- **Express.js:** Lightweight framework for building RESTful APIs.

### Database
- **MongoDB:** NoSQL database for storing tasks.
- **Mongoose:** Object Data Modeling (ODM) library for MongoDB.

---

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AvishkaPriyasad/TodoList-Mern-Stack.git
   
2. **Set Up the Back-End**

      Navigate to the server directory.
      Install dependencies:
      ```bash
      npm install
3. **Set Up the Front-End**

      Navigate to the client directory.
      Install dependencies:
      ```bash
      npm install
      ```
      Start the React development server:
      ```bash
      npm start

4. **Run MongoDB** Ensure you have MongoDB installed and running locally. The database URI is configured as mongodb://127.0.0.1:27017/test.

## Usage
1. Open the application in your browser at http://localhost:3000.
2. Add tasks by entering the task name and clicking the "Add" button.
3. Mark tasks as completed by clicking the circle next to the task.
4. Delete tasks by clicking the trash icon.

## Project Structure
### Front-End
```java
client/
├── src/
│   ├── components/
│   │   ├── Home.jsx
│   │   └── Create.jsx
│   ├── App.jsx
│   └── index.js
├── public/
└── package.json
```
### Back-End

```bash
server/
├── Models/
│   └── Todo.js
├── index.js
├── package.json
```

## Learn More...

Check out the detailed article on how this project was built:  
[Blog article](https://medium.com/@avishkapriyasad/building-a-todo-list-application-with-mern-stack-f0a2950e37d3)
