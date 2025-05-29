pipeline {
    agent any
    stages {
        stage('Build Java') {
            steps {
                bat 'javac helloWorld.java'
                bat 'java helloWorld'
            }
        }
    }
}
