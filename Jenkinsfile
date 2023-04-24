pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code again'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code again.'
                sh 'java Hello'
            }
        }
    }
}