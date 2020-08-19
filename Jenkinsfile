pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo building..'
                sh 'cmake --version'
                sh 'cmake make -DCMAKE_BUILD_TYPE=Debug .. && make -j 4'
            }
        }
        stage('Run') {
            steps {
                sh 'echo running..'
            }
        }
    }
}
