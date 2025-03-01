pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project with Maven...'
                sh 'mvn -B package'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'mvn test'
            }
        }
    }
}