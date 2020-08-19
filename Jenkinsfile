pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'cd build'
                sh 'make        '
            }
        }
        stage('Run') {
            steps {
                sh 'cd build'
                sh './01_override_new_delete.out'
            }
        }
    }
}
