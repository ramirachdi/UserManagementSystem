# 🛠️ **userManagementSystem**

![React](https://img.shields.io/badge/React-v17.0.2-blue?logo=react)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue?logo=docker)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-orange?logo=github)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-green?logo=mongodb)

**userManagementSystem** is a comprehensive web application for managing user information. Built with the MERN stack (MongoDB, NestJS, React, Node.js) and containerized with Docker, it offers features such as user authentication, role-based access control, and CRUD operations on user data.

## 🌟 **Features**

- **User Authentication**: Secure login and signup functionality.
- **Role-Based Access Control**: Different levels of access based on user roles.
- **CRUD Operations**: Create, Read, Update, and Delete user information.
- **Token-Based Authentication**: Uses JWT for secure communication.
- **Docker Containerization**: Simplifies deployment and scaling.

## 📑 **Table of Contents**

- [Technologies Used](#-technologies-used)
- [Getting Started](#-getting-started)
- [Installation](#-installation)
- [Running Tests](#-running-tests)
- [Docker Usage](#-docker-usage)
- [Environment Variables](#-environment-variables)
- [Contributing](#-contributing)
- [License](#-license)

## 💻 **Technologies Used**

- **Frontend**: [ReactJS](https://reactjs.org/) – Building the user interface.
- **Backend**: [NestJS](https://nestjs.com/) – Handling server-side logic.
- **Database**: [MongoDB](https://www.mongodb.com/) – Storing user data.
- **Authentication**: [JWT](https://jwt.io/) – Managing user sessions.
- **Containerization**: [Docker](https://www.docker.com/) – Packaging the application.
- **CI/CD**: [GitHub Actions](https://docs.github.com/en/actions) – Automating testing and deployment.

## 🚀 **Getting Started**

To get a local copy up and running, follow these steps:

### **Prerequisites**

Ensure you have the following installed:

- **Node.js** (v14+): [Download Node.js](https://nodejs.org/)
- **Docker**: [Download Docker](https://www.docker.com/products/docker-desktop/)
- **Git**: [Download Git](https://git-scm.com/)

### **Installation**

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/userManagementSystem.git
    cd userManagementSystem
    ```

2. **Install Dependencies**

    ```bash
    npm install
    ```

3. **Run the Application**

    ```bash
    npm run start:dev
    ```

    Visit `http://localhost:3000` in your browser to access the application.

## 🧪 **Running Tests**

If you have tests, run them with:

- **Unit Tests**

    ```bash
    npm run test
    ```

## 🐳 **Docker Usage**

The application is containerized using Docker. Follow these steps to build and run the Docker containers:

1. **Build the Docker Images**

    ```bash
    docker-compose build
    ```

2. **Run the Docker Containers**

    ```bash
    docker-compose up
    ```

    Access the application at `http://localhost:3000`.

## 🔒 **Environment Variables**

Ensure you set up the following environment variables in a `.env` file located in the `backend` directory:

```plaintext
PORT=5000
MONGO_URI="mongodb+srv://<username>:<password>@cluster.mongodb.net/your-db-name?retryWrites=true&w=majority"
