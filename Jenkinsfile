pipeline {
    agent any

    options {
        scmSkipBuild(deleteBuild: true, preserveBuildNumber: true)
    }

    environment {
        TEST = "Test"
    }

    stages {
        stage('Prepare') {
            steps {
                echo "Prepare"
                //scmSkip(enabled: true, deleteBuild: true, manuallyTriggered: true)
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
