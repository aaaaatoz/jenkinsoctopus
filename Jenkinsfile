#!/usr/bin/env groovy
pipeline {
  agent any
  

  stages {
    stage('Checkout') {
      checkout scm
    }
    stage("Deploy") {
      steps {
        echo "Deploy!"
      }
    }
  }
}
