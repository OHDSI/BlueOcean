pipeline {
  agent any
  stages {
    stage('Update') {
      steps {
        git(url: 'https://github.com/synthetichealth/synthea', branch: 'master')
      }
    }
  }
}