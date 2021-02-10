properties([
  parameters([
    string(name: 'DeploymentType', defaultValue: 'update', description: 'Type of deployment: create or update'),
    string(name: 'Environment', defaultValue: 'sand', description: 'Name of the environment'),
  ])
])
def Version="1-1"

node('master'){
  agent any
  

  stages {
    stage('Checkout') {
      print 'Checkout..'
      checkout scm
    }
    stage("Deploy") {
      sh '''
        echo "Deploy!"
      '''
    }
  }
}
