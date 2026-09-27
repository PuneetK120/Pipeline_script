pipeline {
  agent any;
  triggers {
    githubPush()
  }
  stages {
    stage ('Build') {
      step {
        echo 'This is build stage'
      }
    }
    stage ('Test') {
      step {
        echo 'This is test stage'
      }
    }
    stage ('Deploy') {
      step {
        echo 'This is deploy stage'
      }
    }
  }
}
