pipeline {
    agent any
    
    tools{
        maven 'Maven13'
    }

    stages {
         stage('compile') {
            steps {
               sh 'mvn compile'
            }
        }
         stage('test') {
            steps {
                sh 'mvn test'
            }
        }
         stage('build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
