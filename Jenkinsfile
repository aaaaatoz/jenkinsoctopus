#!/usr/bin/env groovy
pipeline {
  agent any
  

  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }
    stage("Deploy") {
      steps {
        echo "Deploy!"
      }
    }
  }
}
