node {
    stage('chefversion') {
// This step should not normally be used in your script. Consult the inline help for details.
withDockerContainer('chefdf:latest') {
    sh 'chef --version'
}
    }
}
