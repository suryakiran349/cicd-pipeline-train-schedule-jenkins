pipeline {
  agent any
    stage {
      stage('Build'){
        steps {
          echo 'Running build automation'
          sh './gradelw build --no-deamon'
          archiveArtifact artifact: 'dist/train-schedule.zip'
          }
        }
      }
    }
