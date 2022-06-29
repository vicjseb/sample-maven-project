pipeline {
    agent {
    node {
        label 'jenkins-maven-agent'  
         }
    }
    stages {
    stage('maven install') {
      steps {

        sh 'mvn clean install'

      }
    }
  
  }
}
