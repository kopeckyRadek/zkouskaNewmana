pipeline {
  agent {
    docker {
      image 'postman/newman_ubuntu1404'
      args '-v colls:/etc/newman'
    }
  }
  
  stages {
    stage('Postman') {
      steps {
        sh 'echo test'
      }
    }
  }
}