pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo building..'
                sh 'ccmake . '
                sh 'make'
            }
        }
        stage('Run') {
            steps {
                sh 'echo running..'
            }
        }
    }
}
