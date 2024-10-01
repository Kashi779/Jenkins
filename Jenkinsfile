pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Kashi779/war-web-project.git'
            }
        }
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
