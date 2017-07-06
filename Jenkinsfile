pipeline {
  agent any
  stages {
    stage('Prepare') {
      steps {
        git 'https://github.com/ahochsteger/android-gpuimage.git'
      }
    }
    stage('Build') {
      steps {
        sh '''env
./gradlew
'''
      }
    }
    stage('Unit Test') {
      steps {
        sh 'env'
      }
    }
    stage('Acceptance Test') {
      steps {
        sh 'env'
      }
    }
    stage('Integration Test') {
      steps {
        sh 'env'
      }
    }
    stage('Deploy') {
      steps {
        sh 'env'
      }
    }
  }
}