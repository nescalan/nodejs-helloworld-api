pipeline {
    agent any
    tools {
        nodejs 'nodejs'
    }
    stages {
        stage('Build') {
            steps {
                echo "Ejecutar npm install" 
                sh 'npm install'
            }
        }
        stage('Code Test') {
            steps {
                echo "Ejecutar npm test push" 
                sh 'npm test'
            }
        }
    }
}