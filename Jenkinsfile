pipeline {
    agent any  

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'echo $PATH'
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
