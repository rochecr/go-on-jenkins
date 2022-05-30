pipeline {
    agent any
    environment {
        GO11MODULES = 'on'
    }
    tools {
        go 'go-1.18'
    }
    stages {
        stage {
            steps {
                sh 'go build'
            }
        }
    }

}