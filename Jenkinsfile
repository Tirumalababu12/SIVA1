pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "mvn test"
            }
        }
        stage('--compile--') {
            steps {
                sh "mvn compile"
            }
        }

        stage('--package--') {
            steps {
                sh "mvn package"
            }
        }
    }
}

