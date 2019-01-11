pipeline {
  agent any
  stages {
node {
    stage('ChefVersion') {
      agent {
        docker {
          image 'chef/chefdk:3.7.6'
        }

      }
      steps {
        sh 'chef --version'
      }
// This step should not normally be used in your script. Consult the inline help for details.
withDockerContainer('chef/chefdk:current') {
    sh 'chef --version'
}
    }
  }
}
