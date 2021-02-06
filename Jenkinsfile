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
                sh 'mkdir devops4'    
            }
        }
        stage('Deploy') { 
            steps {
                sh 'cd devops4'
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