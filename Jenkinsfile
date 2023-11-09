pipeline {
  agent any
  stages {
    stage('Build Stage'){
      steps {
        sh "chmod +x"
        sh "sh build.sh"
      }
    }
    stage('Publish Stage'){
      steps {
        sh "chmod +x"
        sh "sh publish.sh"
      }
    }
    stage('Deploy Stage'){
      steps {
        sh "chmod +x"
        sh "sh deploy.sh"
      }
    }
  }
}
