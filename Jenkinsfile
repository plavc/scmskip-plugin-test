pipeline {
    agent any

    options {
        scmSkipOptions(enabled: true, deleteBuild: false, manuallyTriggered: true, abortType: 'INTERRUPT')
    }

    stages {
        stage('Build') {
            steps {
                echo "Hello... 23432332fff f ff f f"
            }
        }
        stage('Lint') {
            steps {
                echo "Test "
            }
        }
        stage('Test') {
            steps {
                echo "Test "
            }
        }
    }
}
