pipeline {
  agent any
  stages {
    stage('ChefVersion') {
      agent {
        docker {
          image 'chef/chefdk:3.7.6'
        }

      }
      steps {
        sh 'chef --version'
      }
    }
  }
}
