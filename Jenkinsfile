pipeline {
  agent {
    docker {
      image 'golang:1.10.1-alpine'
      label 'docker-cloud'
    }
    
  }
  stages {
    stage('Hello') {
      steps {
        echo 'HI'
        echo 'Hellooo'
      }
    }
    stage('Hello1') {
      steps {
        echo 'Hellooo1'
      }
    }
  }
}