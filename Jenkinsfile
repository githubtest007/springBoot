pipeline {
  agent {
    node {
      label 'slave-3905'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'mvn install'
      }
    }
  }
  environment {
    REPO_URL = 'https://github.com/githubtest007/springBoot'
  }
}