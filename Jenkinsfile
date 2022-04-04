pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking Out Pipeline'
            }
        }
        stage('Package') {
            steps {
                bat 'mvn clean package'
            }
        }
        stage('Publishing') {
            steps {
                echo 'Publishing'
            }
        }
    }
}
