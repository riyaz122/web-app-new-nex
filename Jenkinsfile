pipeline {
    agent any 
    tools {
        maven 'maven'
    }
    stages{
        stage('Build stage') {
            sh script: 'mvn clean package'
        }
    }
}
