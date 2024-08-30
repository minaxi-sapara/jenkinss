pipeline {
  agent any
  stages {
    stage('git clone') {
      steps {
        git(url: 'https://github.com/minaxi-sapara/jenkinss.git', branch: 'master')
      }
    }

    stage('print') {
      steps {
        sleep 10
      }
    }

    stage('post') {
      steps {
        echo 'hello'
      }
    }

  }
}