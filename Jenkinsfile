pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/MeghaSV20/labexam8.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests....'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
