pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'Node 19.6.1') {
                    sh 'npm config ls'
                    sh 'npm --version'
                }
            }
        }
    }
}
