pipeline {
  agent {
    node {
      label 'slave-3905'
    }
    
  }
  stages {
    stage('check out') {
      steps {
        git(url: 'git@github.com:githubtest007/springBoot.git', branch: 'master')
      }
    }
  }
  environment {
    REPO_URL = 'https://github.com/githubtest007/springBoot'
  }
}