pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/tanwar1d/jenkins-demo-2.git'
            }
        }

        stage('Build') {
            steps {
                bat 'javac Main.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Main'
            }
        }
    }
}
