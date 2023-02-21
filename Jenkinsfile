pipeline {
    agent any  

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
