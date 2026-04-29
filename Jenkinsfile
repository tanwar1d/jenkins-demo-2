pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'echo Building...'
            }
        }

        stage('Force Fail') {
            steps {
                bat 'exit 1'
            }
        }
    }
}
