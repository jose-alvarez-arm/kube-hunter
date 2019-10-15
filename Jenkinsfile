pipeline {
  agent any
  stages {
    stage('Snyk Dep Check') {
      steps {
        snykSecurity(projectName: 'kube-hunter', severity: 'high', snykInstallation: 'Snyk')
      }
    }
  }
}