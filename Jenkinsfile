pipeline {
    agent any

    properties {
        scmSkipBuild(enabled: true, deleteBuild: true)
        
    }

    stages {
        stage('Build') {
            steps {
                scmSkip2(enabled: true, matchAllCommits: true, deleteBuild: false)
            }
        }
    }
}
