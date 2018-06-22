pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('say hello') {
      steps {
        echo 'Welcome to my world !'
        sh 'java -version'
      }
    }
  }
}