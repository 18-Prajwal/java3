pipeline{
  agent any {

    tools {
      maven 'maven'
    }
    stages{
      stage('maven clean') {
        steps {
          sh 'mvn clean'
        }
      }
      stage('mvn compile') {
        steps {
          sh 'mvn compile'
        }
      }
       stage('mvn test') {
        steps {
          sh 'mvn test'
        }
      }
       stage('mvn package') {
        steps {
          sh 'mvn package'
        }
      }
    }
  }
      
        
