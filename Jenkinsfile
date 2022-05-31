pipeline {
    agent any
    tools {
        go 'go-1.18'
    }
    environment {        
        GO111MODULE = 'auto'
    }    
    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}
