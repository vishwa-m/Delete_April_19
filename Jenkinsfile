pipeline {
  agent any
  stages {
    stage('PS1') {
      parallel {
        stage('PS1') {
          steps {
            echo 'Stage1'
          }
        }
        stage('PS2') {
          steps {
            echo 'Hello2'
          }
        }
      }
    }
    stage('Stage2') {
      steps {
        echo 'Hello2'
      }
    }
  }
}