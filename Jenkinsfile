pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                bat 'npm run test'
            }
        }
        stage('Resut') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
