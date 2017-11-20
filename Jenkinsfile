pipeline {
  agent any
  stages {
    stage('Build container') {
      steps {
        git(url: 'https://github.com/PIVX-Delivered/rpc-node.git', branch: 'master', poll: true)
      }
    }
  }
}