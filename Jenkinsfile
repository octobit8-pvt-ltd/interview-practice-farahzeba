pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from repository'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project'
            }
        }
        stage('Code Coverage') {
            steps {
                echo 'Code scanning and coverage'
            }
        }
        stage('Containerization') {
            steps {
                echo 'Creating containers'
            }
        }
        stage('Creating Virtual machine') {
            steps {
                echo 'Provisioning infra'
            }
        }
    }
}
