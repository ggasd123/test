pipeline {
    agent { docker { image 'node:12.7'.0 } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'pwd'
            }
        }
    }
}
