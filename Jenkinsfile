pipeline {
    agent any
    environment {
        GO11MODULES = 'on'
    }
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
