pipeline {
    agent any
    tools {
        maven 'maven3'
    }
    stages('Build'){
        stage{
            sh script: 'mvn clean package'
        }
    }
}

