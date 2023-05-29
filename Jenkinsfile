pipeline  
{
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage('compile') {
            steps {
                sh "mvn compile"
            }
        }
        stage('test') {
            steps {
                sh "mvn test"
            }
        }
        stage('package') {
            steps {
                sh "mvn compile"
            }
        }
        stage('verify') {
            steps {
                sh "mvn compile"
            }
        }
        stage('install') {
            steps {
                sh "mvn compile"
            }
        }
    }
}
            
