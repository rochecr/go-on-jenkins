pipeline {
    agent any
    tools {
        go 'go-1.18'
    }
    environment {
        GO111MODULES = 'on'
    }    
    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}
