pipeline {
    agent { docker 'maven:4.0.0' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}