pipeline {
    agent { label 'agent1' }

    // agent any  

    stages {
        stage('Build') {
            steps {
                nodejs(nodeJSInstallationName: 'Node 19.6.1') {
                       
                    echo 'Building..'
                    sh """
                      npm --version
                      npm install
                    """
                }
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
