pipeline {
    agent: {
        docker: { image 'node:16.1' }
    }
    stages: {
        stage('Testing') {
            steps: {
                sh "echo Node version: \n"
                sh "node --version"
            }
        }
    }

}
