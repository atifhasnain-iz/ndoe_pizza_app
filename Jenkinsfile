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
