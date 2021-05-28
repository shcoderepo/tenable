pipeline {
  agent any
  stages {
    stage('RunPython') {
      steps {
        echo '"Hello World"'
        bat(script: 'cd c:\\\\python', returnStatus: true, returnStdout: true, encoding: 'UTF-8', label: 'python')
        bat(script: 'set "python=C:\\python\\python.exe"  "%python%" script1.py', returnStatus: true, returnStdout: true, label: 'version')
      }
    }

  }
  environment {
    Path = 'C:\\Program Files (x86)\\Common Files\\Oracle\\Java\\javapath;C:\\WINDOWS\\system32;C:\\WINDOWS;C:\\WINDOWS\\System32\\Wbem;C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\;C:\\WINDOWS\\System32\\OpenSSH\\;C:\\Program Files\\Intel\\WiFi\\bin\\;C:\\Program Files\\Common Files\\Intel\\WirelessCommon\\;C:\\Program Files (x86)\\AOMEI Backupper;C:\\Program Files\\Docker\\Docker\\resources\\bin;C:\\ProgramData\\DockerDesktop\\version-bin;C:\\Program Files\\Git\\cmd;C:\\Program Files (x86)\\Intel\\Intel(R) Management Engine Components\\DAL;C:\\Program Files\\Intel\\Intel(R) Management Engine Components\\DAL;C:\\Users\\shivb\\AppData\\Local\\Microsoft\\WindowsApps;C:\\Program Files\\Intel\\WiFi\\bin\\;C:\\Program Files\\Common Files\\Intel\\WirelessCommon\\;C:\\Program Files\\Sublime Text\\;C:\\Users\\shivb\\AppData\\Local\\Programs\\Microsoft VS Code\\bin;C:\\Python;C:\\WINDOWS\\system32\\;C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\;'
  }
}