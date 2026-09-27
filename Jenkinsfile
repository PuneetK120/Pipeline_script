pipeline {
  agent any;
  triggers {
    githubPush()
  }
  stages {
    stage ('Build') {
      steps {
        echo 'This is build stage'
        sh 'sleep 5'
      }
    }
    stage ('Test') {
      steps {
        echo 'This is test stage'
      }
    }
    stage ('Deploy') {
      steps {
        echo 'This is deploy stage'
      }
    }
  }
}
