pipeline {
    agent any
	tools {
	    jdk	'jdk8'
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