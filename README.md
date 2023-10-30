# Task Board - User Task Management Application
## Project Overview

This is a web-based user task management application that allows users to create and manage tasks within lists. The application is built using Node.js, Express.js, React, and PostgreSQL with Sequelize for database management. Users can perform the following tasks:

## Features

- **User Authentication**: Users can create an account and log in using their unique username and password. User credentials are stored securely in the PostgreSQL database.

- **Task Lists Creation**: Users can create multiple task lists, and these lists are saved in the PostgreSQL database. Each list is associated with a user.

- **Drag and Drop Tasks**: Users can easily move tasks from one list to another using HTML's draggable properties. When tasks are moved, the data is automatically updated and saved in the database.

- **Task Data Update**: When a user moves a task to another list, the corresponding list ID is updated in the database to reflect the change.

- **Horizontal Scrolling**: Users can scroll through multiple task lists horizontally, allowing for efficient management of tasks.

- **Task Completion**: Users can mark tasks as completed, and completed tasks are automatically removed from the list, improving task organization.

## Prerequisites

- Node.js and npm installed on your local machine
- PostgreSQL database set up with Sequelize configured


## Technologies

- **Frontend:**
  - React
  - Context API (for state management)
  - Axios (for API requests)
  - React Router (for navigation)
  - Shadcn ui (for UI creation)
  - Tailwind css (for Styling)

- **Backend:**
  - Node.js
  - Express.js
  - Postgres (for data storage)
  - Sequelize

## How to Run This Project Locally
To run this project on your local machine, follow these steps:

- Clone the repository to your local machine:
```bash
git clone https://github.com/nareshkumaralaria/stack-overflow-clone.git

```
- Navigate to the project directory:
```bash
cd stack-overflow-clone

```
#### Install frontend dependencies
- Navigate to the client directory:
```bash
cd client
```

- Install dependencies:
```bash
npm install

```

#### Install backend dependencies
- Navigate to the server directory:
```bash
cd server

```

- Install dependencies:
```bash
npm install

```

### Run the server and client
- Start the backend server
```bash
cd server
npm start 

```


- Start the frontend development server
```bash
cd client
npm run dev

```

### Access the Application
- Open your web browser and access the application at http://localhost:5173.

## Usage

- Create a user account or log in using your existing credentials.
- Create multiple task lists and start adding tasks to them.
- Drag and drop tasks between lists to update and save the data.
- Use horizontal scrolling to navigate through your task lists efficiently.
- Mark tasks as completed to remove them from your lists.

## Demo
For a live demonstration of the Task Board application, please watch the following video:



## Authors

- [@nareshkumaralaria](https://github.com/nareshkumaralaria) (Naresh Kumar)