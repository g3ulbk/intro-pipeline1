pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('say hello') {
      steps {
        echo "Welcome to my ${MY_NAME}'s world !"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Smitha'
  }
}