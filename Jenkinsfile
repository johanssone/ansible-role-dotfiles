pipeline {
  agent {
    dockerfile {
      filename 'asd'
    }

  }
  stages {
    stage('test') {
      steps {
        echo 'test1'
      }
    }
    stage('build') {
      steps {
        sleep 5
      }
    }
  }
}