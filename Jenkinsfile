pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!'
            }
        }
		stage('Stage 2') {
            steps {
                bat 'java -version'
            }
        }
		stage('Stage 3') {
            steps {
                bat 'mvn -v'
            }
        }
    }
}