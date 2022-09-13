pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh './gradlew wrapper --gradle-version 5.0.0'
        echo 'Starting the build automation'
        sh './gradlew build --no-daemon'
      }
    }  
  
  }


}
