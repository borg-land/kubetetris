pipeline {
  agent {
    node {
      label 'ops'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh '''echo Hi
npm install gulp-cli
gulp build'''
      }
    }
  }
}