pipeline {
    agent any 
    stages {
         stage('Jenkins path') {
            steps {
                sh 'pwd'
            }
        }
	stage('clean') { 
            steps {
                sh 'mvn clean'
            }
        }
        stage('validate') { 
            steps {
                sh 'mvn validate'
            }
        }
        stage('compile') { 
            steps {
                sh 'mvn compile'
            }
        }
        stage('test_compile') { 
            steps {
                sh 'mvn test-compile'
            }
        }
        stage('test') { 
            steps {
                sh 'mvn test'
            }
        }
        stage('package') { 
            steps {
                sh 'mvn package'
            }
        }
        stage('install') { 
            steps {
                sh 'mvn install'
            }
        }
        
    }
}
