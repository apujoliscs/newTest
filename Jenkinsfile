pipeline {
  agent any
  stages {
    stage('Check Python Version') {
      steps {
        sh 'python --version'
      }
    }
    stage ('COMSec Login Tests ->') {
      steps {
        bat 'pytest appium_python/Resto/COMSec_LOGIN_test.py'
  }
}
  }
}
