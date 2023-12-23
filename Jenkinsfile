pipeline {
  agent any
  tools {
    maven "maven3.9.6"
  }
  stages {
    stage('build artifacts') {
      steps {
        sh "mvn clean package -DskipTests=true"
        
      }
    }
  }
}
