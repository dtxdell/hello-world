node {
    stage('ChefVersion') {
// This step should not normally be used in your script. Consult the inline help for details.
withDockerContainer('chef/chefdk:current') {
    sh 'chef --version'
}
    }
}
