pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'master'
                    credentialsId: 'github-credentials'
                    url: 'https://github.com/Hassan11-web/gitT.git'

            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}

