pipeline {
  agent any
  stages {
    stage('LEEEEEEEERRRRROYYYY') {
      steps {
        echo 'LEEEERRRROOY JEEEEEEEENKIIIIIINNSSSSSSS'
      }
    }
    stage('Maven Build') {
      steps {
        sh 'mvn clean package -DskipTests'
      }
    }
    stage('Maven Deploy') {
      steps {
        sh 'mvn tomcat7:deploy'
      }
    }
  }
}