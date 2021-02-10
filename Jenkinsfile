pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'terraform init'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'terraform validate'
                
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}