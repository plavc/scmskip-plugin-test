pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                scmSkip2(disabled: false, matchAllCommits: true, deleteBuild: false)
            }
        }
    }
}
