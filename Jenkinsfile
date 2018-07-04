pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('stage1') {
      agent {
        node {
          label 'AliWin'
        }

      }
      steps {
        echo 'hi, stage1.'
      }
    }
  }
  environment {
    hosting = 'compark'
  }
}