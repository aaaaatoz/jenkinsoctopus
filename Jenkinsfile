properties([
  parameters([
    string(name: 'DeploymentType', defaultValue: 'update', description: 'Type of deployment: create or update'),
    string(name: 'Environment', defaultValue: 'sand', description: 'Name of the environment'),
  ])
])
def Version="1-1"

node('master'){
  
  try {
    stage('Checkout') {
      print 'Checkout..'
      checkout scm
    }
    
    stage('Setup Python Venv and Build macro'){
      sh """
        python3 -m venv venv
        . venv/bin/activate
        """
    }
    stage("Deploy") {
      sh '''
        echo "Deploy!"
      '''
    }
  } finally {
    
  }
}
