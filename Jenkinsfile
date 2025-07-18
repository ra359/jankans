/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'ruby:3.4.5-alpine3.22' } }
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
                sh 'echo shit'
            }
        }
    }
}
