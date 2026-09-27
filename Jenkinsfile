pipeline {
  agent any;
  triggers {
    githubPush()
  }
  stages {
    stage ('Build') {
      step {
        echo 'This is build stage'
        sh 'sleep 5'
      }
    }
    stage ('Test') {
      step {
        echo 'This is test stage'
        sh 'sleep 10'
      }
    }
    stage ('Deploy') {
      step {
        echo 'This is deploy stage'
      }
    }
  }
}
