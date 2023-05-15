pipeline {
  agent any
  stages {
    stage('Zip') {
      steps {
        sh 'zip * server_resources.zip'
      }
    }

    stage('Archive') {
      steps {
        archiveArtifacts '*.zip'
      }
    }

  }
}