pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('say hello') {
      steps {
        echo "Welcome to ${params.Name}'s world !"
        sh 'java -version'
        echo "${TEST_USER_USR}"
        echo "${TEST_USER_PSW}"
      }
    }
  }
  environment {
    MY_NAME = 'Smitha'
    TEST_USER = credentials('test-user')
  }
  parameters {
    string(name: 'Name', defaultValue: 'whoever you are', description: 'Who should I say hi to?')
  }
}