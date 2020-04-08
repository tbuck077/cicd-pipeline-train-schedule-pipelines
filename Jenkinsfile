pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echoh 'Running build automation'    
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: '/dist/trainSchedule.zip'
   }
   
  { 
}
