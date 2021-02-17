pipeline {
    agent any 
    tools {
        maven 'maven'
    }
    stages{
        stage('Build stage') {
             sh  'mvn clean package'
        }
    }
}
