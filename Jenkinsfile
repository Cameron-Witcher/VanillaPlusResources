pipeline {
  agent any
  stages {
    stage('Zip') {
      steps {
        sh 'zip  -r * server_resources.zip'
      }
    }

    stage('Archive') {
      steps {
        archiveArtifacts '*.zip'
      }
    }

  }
}