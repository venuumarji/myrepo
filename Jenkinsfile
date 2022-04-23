pipeline {
  agent {label 'tomcat'}
  stages {
    stage('check') {
      steps {
              sh 'pwd'
              sh 'echo "hi"'
              sh 'free -m'
              sh 'ls -a'
      }
    }
  }
}    
