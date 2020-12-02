pipeline {
  agent any
    stages {
      stage("build") {
        steps {
          echo 'building the application'
          sh 'npm install'
        }
      }
      stage("test") {
        steps {
          echo 'running tests - is this working'
          sh 'npm test'
        }
      }
      stage("deploy") {
        steps {
          echo 'deploying the application'

        }
      }
    }
}
