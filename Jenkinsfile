pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out source code'
            }
        }

        stage('Lint Validation') {
            steps {
                echo 'Running lint validation'
            }
        }

        stage('Build') {
            steps {
                echo 'Build Successful'
            }
        }

        stage('Unit Test') {
            steps {
                echo 'Running unit tests'
            }
        }

        stage('Code Validation') {
            steps {
                echo 'Code validation completed successfully'
            }
        }
    }

    post {
        success {
            echo 'CI Pipeline Passed'
        }

        failure {
            echo 'CI Pipeline Failed'
        }
    }
}
