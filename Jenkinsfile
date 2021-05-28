pipeline {
  agent any
  stages {
    stage('RunPython') {
      steps {
        echo '"Hello World"'
        bat(script: 'cd C:\\Users\\shivb\\AppData\\Local\\Microsoft\\WindowsApps', returnStatus: true, returnStdout: true, encoding: 'UTF-8', label: 'python')
        bat(script: 'C:\\Users\\shivb\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe --version', returnStatus: true, returnStdout: true, label: 'version1')
      }
    }

  }
  environment {
    Path = 'C:\\\\WINDOWS\\\\SYSTEM32;C:\\Users\\shivb\\AppData\\Local\\Microsoft\\WindowsApps'
  }
}