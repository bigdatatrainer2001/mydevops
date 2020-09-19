pipeline {
  agent any
  stages {
    stage('pull the code') {
      steps {
        build(job: 'MyDemo', wait: true)
      }
    }

    stage('end') {
      steps {
        echo 'done'
      }
    }

  }
}