pipeline {
  agent any
  stages {
    stage('Build Stage'){
      steps {
        sh "chmod +x build.sh"
        sh "sh build.sh"
      }
    }
    stage('Publish Stage'){
      steps {
        sh "chmod +x publish.sh"
        sh "sh publish.sh"
      }
    }
    stage('Deploy Stage'){
      steps {
        sh "chmod +x deploy.sh"
        sh "sh deploy.sh"
      }
    }
  }
}
