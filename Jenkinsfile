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
                sh 'mkdir devops2'    
            }
        }
        stage('Deploy') { 
            steps {
                sh 'cd devops2'
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