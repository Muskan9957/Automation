pipeline {
  agent any
  stages {
    stage('Build Stage') {
      steps {
        sleep 2
        echo 'Executing build stage'
        sh 'echo "you can run NPM/Gradle etc"'
      }
    }

  }
  environment {
    task = 'demo'
    tag = '0.2.4'
  }
}