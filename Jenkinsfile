pipeline {
    agent {
    environment {
        // Override HOME to WORKSPACE
        HOME = "${WORKSPACE}"
        // or override default cache directory (~/.npm)
        NPM_CONFIG_CACHE = "${WORKSPACE}/.npm"
    }

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}
