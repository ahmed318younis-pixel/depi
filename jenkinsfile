pipeline {
    agent any

    stages {
        stage('Echo File') {
            steps {
                sh 'echo "Hello from Jenkins!" > myfile.txt'
                sh 'cat myfile.txt'
            }
        }
    }
}

