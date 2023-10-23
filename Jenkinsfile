pipeline {
    agent any 
    stages {
        stage('Checkout') { 
            steps {
                
            }
        }
        stage('Build') { 
            steps {
                sh 'mvn clean package' 
            }
        }
        stage('Test') { 
            steps {
                sh 'mvn test'
            }
        }
    }
}