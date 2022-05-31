pipeline {
    agent any
    tools {
        go 'go-1.18'
    }

    stages {
        stage('Build') {
            steps {
                go env -w GO111MODULE=auto
                sh 'go build'
            }
        }
    }
}
