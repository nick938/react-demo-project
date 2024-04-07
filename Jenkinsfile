Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'node:16' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}