pipeline {
  agent any
  tools {
    maven 'M2_HOME'
  }
  
  stages {
    stage('build') {
      steps {
       echo 'Hello build'
        sleep 10
         
      }
    }
    stage('test') {
      steps {
        echo 'Hello test'
        sleep 5        
      }
    }
    stage('deploy') {
      steps {
        echo 'Hello deploy'
        sh 'pwd'       
      }
    }
    stage('push') {
      steps {
        echo 'Hello push'
        sh 'docker ps'
      
      }
    }
  }
}
