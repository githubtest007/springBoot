pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            acceptGitLabMR(mergeCommitMessage: 'll')
          }
        }
        stage('test') {
          steps {
            sh 'ls'
          }
        }
      }
    }
  }
}