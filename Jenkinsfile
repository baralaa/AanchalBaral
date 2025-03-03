pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/baralaa/AanchalBaral.git'
            }
        }
        stage('Build') {
            steps {
                sh 'javac src/Main.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java src.Main'
            }
        }
    }
}
