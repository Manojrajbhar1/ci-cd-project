pipeline {
    agent any

    environment {
        NEXUS_CREDS = credentials('nexus_creds')
        NEXUS_DOCKER_REPO = 'localhost:8082'
    }

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Manojrajbhar1/maven-web-app.git'
            }
        }
