pipeline {
  agent any
  stages {
    stage('Initial') {
      steps {
        echo 'iniciando a contruÁŠo do meu pipeline'
      }
    }
    stage('Build') {
      steps {
        git 'https://github.com/Hirondina/JavaUnitTest.git'
      }
    }
    stage('Test') {
      steps {
        bat 'echo "Tesntando o pipeline"'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Sucess!!!'
      }
    }
  }
}