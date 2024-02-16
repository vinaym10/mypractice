pipeline {
  agent {
    node {
      label 'nod2'
    }

  }
  stages {
    stage('stage1') {
      steps {
        sh 'echo "hello world"'
      }
    }

    stage('stage2') {
      steps {
        sh 'touch index.html'
      }
    }

  }
}