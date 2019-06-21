pipeline {
  agent any

  environment {

    PATH = "C:\\WINDOWS\\SYSTEM32"

}

  stages {
    stage('docker') {
      steps {
        echo 'docker in win '
      }
    }
    
    stage('docker command'){
    
      steps{
      
        echo  'executing docker command'
      
        bat 'docker version'
      }
    }
  }
}
