pipeline {
    agent any
    tools { 
        maven 'apache-maven-3.5.0' 
        jdk 'jdk8' 
    }
    stages {
        stage ('Initialize') {
            steps {
                echo 'Hello World' 
            }
        }

        stage ('Build') {
            steps {
                echo 'This is a minimal pipeline.'
            }
        }
    }
}