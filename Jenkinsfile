pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'sh mvn test'
      }
    }

    stage('compile') {
      steps {
        sh 'sh mvn compile'
      }
    }

    stage('build') {
      steps {
        sh 'sh mvn build'
      }
    }

  }
}