pipeline {
  agent any
    stage {
      stage('Build'){
        steps {
          echo 'Running build automation'
          sh './gradelw build --no-daemon'
          archiveArtifacts artifacts: 'dist/train-schedule.zip'
          }
        }
      }
    }
