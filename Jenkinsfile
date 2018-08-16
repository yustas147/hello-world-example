pipeline {
  agent any
  stages {
    stage('Branch') {
      steps {
        withMaven(maven: 'M3') {
          sh 'mvn clean install'
        }

      }
    }
  }
}