pipeline {
    agent any

    stages {
        stage('Checkout HTML and CSS') {
            steps {
                // Checkout HTML and CSS files from version control
                git 'https://github.com/vinaym10/mypractice.git'
            }
        }
        stage('Deploy HTML and CSS') {
            steps {
                // Copy HTML and CSS files to web server directory
                sh 'cp index.html /var/www/html/'
                sh 'cp styles.css /var/www/html/'
            }
        }
    }
}
