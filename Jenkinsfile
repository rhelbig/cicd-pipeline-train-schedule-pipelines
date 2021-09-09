pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
      echo 'Running build automation'
      sh './gadlew build --no-deamon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
}
