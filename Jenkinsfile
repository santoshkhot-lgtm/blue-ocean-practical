
pipeline {
    agent any

    stages {
        stage('Welcome') {
            steps {
                echo 'Welcome to Blue Ocean!'
            }
        }

        stage('Linux Information') {
            steps {
                sh 'whoami'
                sh 'hostname'
                sh 'date'
            }
        }

        stage('Build Success') {
            steps {
                echo 'Pipeline completed successfully!'
            }
        }
    }
}
