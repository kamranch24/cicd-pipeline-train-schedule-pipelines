pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh './gradlew wrapper --gradle-version=5.1.1'
        echo 'Starting the build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }  
  
  }


}
