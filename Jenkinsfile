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
    when {
     branch "source1"
    }
   steps {
    sh 'cat README.md'
     }
   }
  stage('sayinng hello')
  {
   when {
    branch "source2"
   }
  steps {
  echo "Hello"
   }
  }
  stage('greeting')
   {
    when {
     branch "source1"
    }
   steps {
     echo "Hello India"
      }
    }
  }
}
