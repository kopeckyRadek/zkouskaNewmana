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
        sh 'echo test1'
		sh 'newman run colls/col1.json'
		sh 'echo test2'
      }
    }
  }
}