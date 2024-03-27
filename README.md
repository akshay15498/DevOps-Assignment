# Node.js REST API with Dockerization

# Getting Started #
To run the API locally or in a Docker container, follow these steps:

Download Files: Download the assignment files from the provided link.

Check Node.js Installation: Ensure Node.js is installed on your computer. If not, download and install it from the official Node.js website.

Install Dependencies: Run npm install in the terminal to install required dependencies.

Run the Server: Execute node main.js to start the Node.js server. Access the API at http://localhost:3000 to see the "Hello, World!" response.

# Dockerization #
To run the API in a Docker container, follow these additional steps:

Create Dockerfile: Create a Dockerfile in the project directory with the provided content.

Build Docker Image: Build the Docker image using docker build -t my-node-app .

Run Docker Container: Run the Docker container with docker run -p 3000:3000 my-node-app.
