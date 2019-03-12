pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('') {
      steps {
        echo 'printf33'
        sleep(unit: 'SECONDS', time: 3)
      }
    }
    stage('r') {
      steps {
        sleep 4
      }
    }
  }
  environment {
    Name = 'test'
  }
}