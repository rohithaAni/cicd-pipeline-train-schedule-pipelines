pipeline {
  agent any
  stages  {
    stage('Build'){
    steps {
      echo 'Running build atmosphere' 
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
 }
}
