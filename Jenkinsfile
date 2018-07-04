pipeline {
  agent {
    node {
      label 'AliWin'
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
    cloud = 'Aliyun'
  }
}