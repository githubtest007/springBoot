pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        acceptGitLabMR(mergeCommitMessage: 'll')
      }
    }
  }
}