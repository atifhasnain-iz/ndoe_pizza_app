pipeline {
    agent any 
    
    environment {
        PATH = "/home/jenkins/.nvm/versions/node/v19.6.1/bin/:${env.PATH}"
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh """
                  echo $PATH
                  pwd
                  whoami
                  node -v
                  npm -v
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
