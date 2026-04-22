pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build en cours...'
            }
        }

        stage('Test') {
            steps {
                echo 'Tests OK'
            }
        }

        stage('Run script') {
            steps {
                bat 'test.bat'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy simulé'
            }
        }
    }
}
