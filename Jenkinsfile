pipeline{
agent any 
options {
 buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')
}
 stages {
  stage('Print Java')
  {
   steps {
     sh 'java -version'
      }
  }
  stage('cat README')
   {
   steps {
    sh 'cat README.md'
     }
   }
  stage('sayinng hello')
  {
  steps {
  echo "Hello"
   }
  }
  stage('greeting')
   {
   steps {
     echo "Hello India"
      }
    }
  }
}
