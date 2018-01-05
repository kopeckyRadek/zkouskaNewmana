pipeline {
  agent {
    docker {
      image 'postman/newman_ubuntu1404'
      args '-v ./colls:/etc/newman --collection="col1.json"'
    }
    
  }
  stages {
    stage('Postman') {
      steps {
        sh 'echo testik'
      }
    }
  }
}