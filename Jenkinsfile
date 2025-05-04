pipeline{
  agent any
  environment{
    PATH="/opt/maven/bin:$PATH"  // to set maven path
  }
  stages{
    stage('build war'){
      steps{
        sh 'mvn clean install'
      }
    }
  }
}
