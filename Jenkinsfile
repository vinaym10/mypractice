pipeline {
  agent any
  stages {
    stage ('Checkout HTML and CSS') {
      steps {
        git credentialsId: 'vinaym10', url: 'https://github.com/vinaym10/mypractice.git'
      }
    }
   stage ('Deploy HTML and CSS') {
     steps {
       sh 'cp index.html /var/ww/html/'
       sh 'cp styles.css /var/ww/html/'
     }
   } 
  }
}
