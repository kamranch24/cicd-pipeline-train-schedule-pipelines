pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'Starting the build automation'
        sh './gradlew build --no-daemon'
        ArchiveArtifacts artifacts:'dist/trainSchedule.zip'
      }
    }  
  
  }


}
