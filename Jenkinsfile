pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo "Hellooo ${params.Namae}!"
      }
    }
    stage('Deploy') {
      input {
        message 'Should we continue?'
      }
      steps {
        echo 'Continuing with deployment'
      }
    }
  }
}