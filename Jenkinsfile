pipeline {
  agent any
  stages {
    stage('git pull') {
      steps {
        git(url: 'https://github.com/chandrs/pipeline-examples.git', branch: 'master', changelog: true)
      }
    }
  }
}