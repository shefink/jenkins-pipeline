pipeline {
    agent any

    stages {
        stage('clone from github') {
            steps {
                git branch: 'main', url: 'https://github.com/mohammedashiqu/jenkins-pipeline.git'
            }
        }
        stage('building...') {
            steps {
                echo "build"
            }
        }
        stage('testing') {
            steps {
                echo "test"
            }
        }
        stage('Deploying') {
            steps {
                echo "Deployment"
            }
        }
    }
}
