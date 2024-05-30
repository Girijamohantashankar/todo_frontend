# Todo App

A simple and functional Todo application that allows users to manage their daily tasks. This full-stack application is built with HTML, CSS, and JavaScript for the frontend and Node.js, Express, and MongoDB for the backend.

## Features

- Add, update, and delete tasks.
- Mark tasks as complete.
- Persistent storage with MongoDB.
- Responsive design for various devices.

## Technologies Used

### Frontend

- **HTML5:** Structure of the application.
- **CSS3:** Styling and layout.
- **JavaScript:** Interactivity and DOM manipulation.

### Backend

- **Node.js:** JavaScript runtime for server-side logic.
- **Express.js:** Web framework for Node.js to build RESTful APIs.
- **MongoDB:** NoSQL database for storing tasks.

## Demo

![Demo Image](image/home.png)

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB instance running locally or a cloud MongoDB service.

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Girijamohantashankar/todo_frontend.git
    cd todo-app
    ```

2. **Install backend dependencies:**
    ```sh
    npm install
    ```

3. **Set up environment variables:** Create a `.env` file in the root of the project with the following content:
    ```sh
    MONGODB_URI=your_mongodb_connection_string
    PORT=5000
    ```

4. **Run the backend server:**
    ```sh
    npm start
    ```

5. **Serve the frontend:** Open `index.html` in your browser or use a local server to serve static files.

## Usage

- Open the application in your browser.
- Add tasks using the input field and the "Add" button.
- Mark tasks as complete by clicking on the checkbox.
- Edit or delete tasks using the provided buttons.

## Project Structure

```plaintext
todo-app/
│
├── backend/
│   ├── models/
│   │   └── Task.js
│   ├── routes/
│   │   └── tasks.js
│   ├── .env
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── scripts.js
│   ├── index.html
│
└── README.md
