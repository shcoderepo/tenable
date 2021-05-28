pipeline {
  agent any
  stages {
    stage('RunPython') {
      steps {
        echo '"Hello World"'
        bat(script: 'cd c:\\\\python', returnStatus: true, returnStdout: true, encoding: 'UTF-8', label: 'python')
        bat(script: 'python --version', returnStatus: true, returnStdout: true, label: 'version1')
      }
    }

  }
  environment {
    Path = 'C:\\Users\\shivb\\AppData\\Local\\Microsoft\\WindowsApps'
  }
}