pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        sh '''echo "Welcome to New Pipeline View"
echo "#############################################"
echo "Polling done"
echo "Proceeding next step...."'''
      }
    }
    stage('Build') {
      steps {
        echo 'Build EAR done'
      }
    }
    stage('Unit Test') {
      steps {
        sh '''echo "Imlemented test"
'''
      }
    }
    stage('Confluence') {
      steps {
        sh 'echo "Added the confluence Page"'
      }
    }
  }
}