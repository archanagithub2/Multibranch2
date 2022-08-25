pipeline{
agent any 
options {
 buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')
}
 stages {
  stage('coning'){
   steps{
      git branch: 'main', credentialsId: '66d424f0-830b-4b76-b681-d5ec93840b3c', url: 'https://github.com/archanagithub2/Multibranch2.git'
   }
  }
  
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
