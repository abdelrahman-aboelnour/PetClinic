
pipeline {
    agent { docker { image 'maven:3.8.7-eclipse-temurin-11' args '--privileged' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}