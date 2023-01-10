pipeline {
    agent any
    stages {
        stage('validate installation') {
            steps {
                sh 'java --version'
                sh 'mvn --version'
            }
        }
		stage('build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}