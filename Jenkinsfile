pipeline {
    agent any

    options {
        scmSkipOptions(enabled: true, deleteBuild: false, manuallyTriggered: true)
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
    }
}
