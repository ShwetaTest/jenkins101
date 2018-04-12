library 'SharedLibs'
pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('ShwetaM') {
      steps {
        sh 'mvn -v'
      }
    }
     stage('Shared Lib') {
         steps {
             helloWorld("Jenkins")
         }
      }
  }
}
