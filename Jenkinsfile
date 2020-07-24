pipeline {
    agent { docker { image 'node:12.18.2' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'pwd'
            }
        }
    }
}
