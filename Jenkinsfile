pipeline {
  agent any
  stages  {
    stage('Build'){
    steps {
      echo 'Running build atmosphere' 
      sh './gradlew build --no-daemon'
      archive Artifacts artifacts: 'dist/trainSchedule.zip'

   }
  }
 }
}
