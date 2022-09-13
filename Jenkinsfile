pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh './gradlew wrapper --gradle-version 7.5.1'
        echo 'Starting the build automation'
        sh './gradlew build --no-daemon'
      }
    }  
  
  }


}
