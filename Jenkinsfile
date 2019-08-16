pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh label: '', script: 'java -version'
            }
        }
        /*stage('Test') { 
            steps {
                git credentialsId: 'b4284707-2b39-4b70-bee0-9700d60ce11b', url: 'https://github.com/sreedharpaladugu93/javatemp'
            }
        }*/
        stage('Deploy') { 
            steps {
                sleep time: 10, unit: 'NANOSECONDS' 
            }
        }
    stage('added') { 
            steps {
                ps -ef
            }
        }
    }
}
