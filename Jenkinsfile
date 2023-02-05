pipeline {
    agent { docker { image 'maven:3.8.7-eclipse-temurin-11' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }            
        }
        stage('sys check') {
            steps {
                sh 'lscpu'
            }
        }
    }    
    }
