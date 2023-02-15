pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'g++ -o file_exec file.cpp'
            }
        }
        stage('Test') {
            steps {
                sh './file_'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment successful for PES1UG20CS252'
            }
        }
    }

    post {
        
        failure {
            echo 'Pipeline failed.'
        }
    }
}
