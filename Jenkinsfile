pipeline {
  agent any
  stages {
    stage('ChefVersion') {
      agent {
        docker {
          image 'chef/chefdk:current'
        }

      }
      steps {
        sh 'chef --version'
      }
    }
  }
}