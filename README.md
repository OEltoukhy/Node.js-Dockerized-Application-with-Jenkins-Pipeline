# Node.js-Dockerized-Application-with-Jenkins-Pipeline
This repository contains a Node.js application Dockerized for both development and production environments, along with a Jenkins pipeline script for automated CI/CD.

Application Code
The application code consists of two main parts:

Node.js Express Server
The index.js file in the root directory contains a simple Node.js Express server. It listens on port 3000 and responds with a "Hello Omar Eltoukhy" message when accessed.

Docker Configuration
The docker-compose.yml file defines Docker services for both development and production environments. It specifies the Docker images to build and run, as well as environment variables and volumes.

Jenkins Pipeline
The Jenkins pipeline script, Jenkinsfile, automates the CI/CD process. It defines stages for initialization, testing, building, and deployment. Each stage executes specific tasks using Groovy functions defined in the script.groovy file.

Prerequisites
To run this application and pipeline, you need the following installed on your system:

Docker
Jenkins
Getting Started
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/your-repository.git
Set up Docker and Jenkins on your system if you haven't already.

Customize the application code and pipeline script according to your requirements.

Run the Jenkins pipeline to automate the CI/CD process.

Usage
Start the development environment:

bash
Copy code
docker-compose -f docker-compose.dev.yml up
Start the production environment:

bash
Copy code
docker-compose -f docker-compose.prod.yml up
Access the application in your web browser at http://localhost:3000.

Contributing
Contributions are welcome! Please feel free to submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
