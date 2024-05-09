pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                echo 'build'
                sh 'ls'
            }
        }
        stage('Stage 2') { // Changed stage name to 'Stage 2' to avoid duplication
            steps {
                echo 'build'
                sh '''
                pwd
                '''
            }
        }
    }
}
