pipeline {
  agent any
  stages {
    stage('DEPLOY') {
      steps {
        sh 'cp index.cgi /usr/share/nginx/https/cgi.bin/'
        sh 'chmod 755 /usr/share/nginx/https/cgi.bin/index.cgi'
      }
    }

  }
}
