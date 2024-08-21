def projects = [
  'msa-sample-api-master',
  'msa-sample-gateway-master',
  'msa-sample-sd-api-master',
  'msa-sample-ui-master'
]

pipeline {
  agent any

  tools {
    maven 'maven'
  }


  stages {
    stage('Checkout Projects') {
      steps {
        git url: 'https://github.com/ygm0516/CICD-project.git', credentialsId:'ygm-token', branch: 'main'
      }
    }

}
}
