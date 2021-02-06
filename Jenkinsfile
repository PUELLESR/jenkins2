pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'pwd' 
            }
        }
        stage('Test') { 
            steps {
                sh 'mkdir devops3'    
            }
        }
        stage('Deploy') { 
            steps {
                sh 'cd devops3'
                sh 'pwd'
            }
        }

        stage('Notificacion') { 
            steps {
                sh 'pwd'
            }
        }
    }
}