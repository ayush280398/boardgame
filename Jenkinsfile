pipeline {
    agent any
    tools{
        maven 'maven3.9'
        jdk 'jdk17'
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
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
        
