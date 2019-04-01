pipleline {
  agent any
  stages {
    stage ('Build') {
      stes {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archivedArtifacts artifacts: 'dist/trainSchedule.zip'      
      }
    }  
  }
}
