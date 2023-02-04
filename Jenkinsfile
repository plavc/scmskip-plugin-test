pipeline {
    agent any

    options {
        scmSkipOptions(enabled: true, deleteBuild: true, manuallyTriggered: false)
    }

    stages {
        stage('Prepare') {
            steps {
                echo "Prepare"
            }
        }
        stage('Lint') {
            steps {
                echo "Lint"
            }
        }
        stage('Test') {
            steps {
                echo "Test"
            }
        }
        stage('Docker: Lint') {
            steps {
                echo "Docker Lint"
            }
        }
        stage('Docker: Build') {
            steps {
                echo "Docker Build"
            }
        }
        stage('Docker: Push') {
            steps {
                echo "Docker Push"
            }
        }
    }
}
