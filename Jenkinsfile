pipeline {
    agent any
    
    stages {
        stage("Clone Code") {
            steps {
                git url: "https://github.com/LondheShubham153/node-todo-cicd.git", branch: "master"
                echo 'Code has been cloned successfully.'
            }
        }
        stage("Build and Test") {
            steps {
                // Add commands to build and test your application
                echo 'Building and testing the code...'
                // Example: npm install, npm test
            }
        }
        stage("Security Scan") {
            steps {
                // Add steps to perform security scans
                echo 'Performing security scan...'
            }
        }
        stage("Push to Docker Hub") {
            steps {
                // Add steps to push the image to Docker Hub
                echo 'Pushing the image to Docker Hub...'
            }
        }
        stage("Deploy") {
            steps {
                // Add steps to deploy the application
                echo 'Deploying the application...'
            }
        }
    }
}
