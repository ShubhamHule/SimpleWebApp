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
                echo 'Packaging'
            }
        }
        stage('Publishing') {
            steps {
                eco 'Publishing'
            }
        }
    }
}
