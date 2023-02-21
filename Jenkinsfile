pipeline {
    agent { label 'agent1' }

    tools { 'Node 6.0' }
    // agent any  

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh """
                  npm --version
                  npm install
                """
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
