pipeline {
    agent any
    tools {
        go 'go-1.16.3'
    }
    environment {
        GO111MODULE = 'on'
    }
    stages {
        stage('Build') {
            steps {
                bat 'go build'
            }
        }
    }
}
