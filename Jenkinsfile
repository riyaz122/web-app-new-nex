pipeline {
    agent any
    environment {
        PATH = "/opt/apache-maven-3.6.3/bin:$PATH"
    }
    stages('Build'){
        steps{
            
            sh "mvn clean package"
        }
    }
}


