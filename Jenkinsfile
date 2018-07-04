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
        bat(returnStatus: true, returnStdout: true, script: 'bluewin.bat', encoding: 'utf-8')
      }
    }
  }
  environment {
    cloud = 'Aliyun'
  }
}