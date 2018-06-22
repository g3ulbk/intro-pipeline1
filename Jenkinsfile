pipeline {
  agent {
    label 'jdk8'
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