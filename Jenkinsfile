pipeline {
    agent any
    tools{
        maven 'maven-3.8.6'
    }
    stages{
        stage('Build Maven'){
            steps{
                sh 'mvn clean install'
            }
        }
    }
}