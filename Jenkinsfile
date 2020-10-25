pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh "docker build -t vuejs-cookbook/dockerize-vuejs-app ."
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}