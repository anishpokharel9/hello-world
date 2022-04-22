pipeline {
  agent any

  stages('CI') {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }

    stage('Build') {
      steps {
        // script
         mvn clean package
      }
    }

    stage('Test') {
      steps {
         mvn test
      }
    }
  }

}