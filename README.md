# JSON Server Backend

This repository contains the JSON server setup for serving a mock backend API using a simple JSON file (`db.json`). This backend can be used for development and testing purposes, mimicking the behavior of a real RESTful API for user authentication in your Angular login application.

## Features

- Provides a REST API using a JSON file as the database.
- Supports all CRUD operations (Create, Read, Update, Delete).
- Simple setup with no external database required.
- Predefined user credentials for testing login functionality.

## Prerequisites

Before setting up the JSON server, ensure you have the following installed:

- [Node.js](https://nodejs.org/en/) (LTS version recommended)
- npm (Node Package Manager, included with Node.js)

## Getting Started

### 1. Clone the Repository

To get started, first clone this repository to your local machine:

git clone https://github.com/fatmaindex/json-server-backend.git
cd json-server-backend

### 2. Set up the JSON server for user authentication:

- Start the JSON server (from the `json-server-backend` folder):

      ```bash
      npx json-server --watch db.json
      ```
     ```bash
    -json-server --watch db.json -p 3003
      ```
    - This will start the backend server at `http://localhost:3003`.
