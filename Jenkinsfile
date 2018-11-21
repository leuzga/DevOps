pipeline {
  agent {
    docker {
      image 'node8.11.1'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'sh \'npm --version\''
      }
    }
  }
}