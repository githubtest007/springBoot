pipeline {
  agent {
    node {
      label 'slave-3905'
    }
    
  }
  stages {
    stage('build') {
      agent any
      environment {
        mvn3 = '/opt/apache-maven-3.2.5'
      }
      steps {
        sh 'mvn install'
      }
    }
  }
}