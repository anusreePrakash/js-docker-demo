pipeline {
  agent any
    stages {
      stage("build") {
        steps {
          echo 'building the application'
        }
      }
      stage("test") {
        steps {
          echo 'running tests'
          sh 'npm install'
        }
      }
      stage("deploy") {
        steps {
          echo 'deploying the application'
          sh 'npm test'
        }
      }

    }
}
