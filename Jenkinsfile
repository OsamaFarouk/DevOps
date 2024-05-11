pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'build'
                sh '''
                    docker build -t 0samaa/bakehouse:latest

                '''
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

#done
