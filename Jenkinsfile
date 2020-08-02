pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'df -h'
            echo 'hello'
          }
        }

        stage('test') {
          steps {
            sh 'fd'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        sh '''ddddd
ps -ef
'''
        sleep 10
      }
    }

  }
}