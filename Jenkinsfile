pipeline {
   agent any

  stages {
    stage('Checkout') {
      steps {
        echo 'Checkout'
        checkout scm
      }
    }

    stage('Build') {
      steps {
        // script
         echo 'Build'
        sh 'mvn clean install'
      }
    }
    
    stage('Test') {
      steps {
        // script
         echo 'Build'
        sh 'mvn test'
      }
    }

  }

}