pipeline {
    agent any
    tools {
        go 'go-1.18'
    }
    environment {        
        GO111MODULE = ''
    }    
    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}
