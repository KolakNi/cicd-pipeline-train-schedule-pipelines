pipeline{
agent any
stages {
  stage ("Build"){
  steps{
     echo 'some text and runing build automation'
     sh './gradlew build --no-daemon'
     archiveArtifacts artifacts: 'dist/trainSchedule.zip'
   }
  }
}

}
