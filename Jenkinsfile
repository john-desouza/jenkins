pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      agent any
      steps {
        echo 'Bees Buzz!'
        junit '**/surefire-reports/**/*.xml'
      }
    }

  }
}