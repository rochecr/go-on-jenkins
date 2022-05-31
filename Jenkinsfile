pipeline {
    agent any
    tools {
        go 'go-1.18'
    }

    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}
