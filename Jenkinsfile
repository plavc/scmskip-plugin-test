pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                scmSkip(disabled: false, matchAllCommits: true, deleteBuild: false)
            }
        }
    }
}
