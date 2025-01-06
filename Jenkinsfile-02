pipeline {
    agent any
	tools {
        maven 'maven-3.6.3' 
    }
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!'
            }
        }
		stage('Stage 2') {
            steps {
                bat 'mvn -v'
            }
        }
    }
}