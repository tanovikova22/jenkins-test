pipeline {
    agent {
        docker { image 'node:18' }
    }
    stages {
        stage('Testing') {
            steps {
                sh "echo Node version: \n"
                sh "node --version"
            }
        }
    }

}
