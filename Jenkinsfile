pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
date'''
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'test ppppppp'
          }
        }

        stage('test par') {
          steps {
            echo 'print proogress'
            echo 'test print parler'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy msg'
        sleep 13
      }
    }

  }
}