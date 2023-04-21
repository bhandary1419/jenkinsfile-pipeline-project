pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
        }
       stage('test') {
            steps {
                echo "This is test file and I am testing it"
                sh 'echo using shell within Jenkinsfile-2nd'
                echo 'not using shell in the Jenkinsfile-3rd'
            }
        }
    }
}