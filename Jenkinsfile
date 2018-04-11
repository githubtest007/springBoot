pipeline {
  agent any
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