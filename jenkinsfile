pipeline {
    agent any
    tools{
      maven 'M2_HOME'
    }
     stages{
      stage('clean'){
       steps {
         sh 'mvn clean'
       }
    }
    stage('compile'){
      steps{
        sh 'mvn compile'
      }
    }
    stage('install, package'){
      steps{
        sh 'mvn install'
        sh 'mvn package'
      }
    }
    }

}
