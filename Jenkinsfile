pipeline {
  agent any
  stages {
    stage('Build Stage'){
      steps {
      sh "sh build.sh"
      }
    }
    stage('Publish Stage'){
      steps {
        sh "sh publish.sh"
      }
    }
        stage('Deploy Stage'){
      steps {
        sh "sh deploy.sh"
      }
    }
  }
}
