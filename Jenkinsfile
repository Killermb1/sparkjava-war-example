pipeline{
  agent any
  environment{
    PATH="/opt/maven/bin:$PATH"
  }
  stages{
    stage('build war'){
      steps{
        sh 'mvn clean install'
      }
    }
  }
}
