pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'C:/Users/SQJLCHOO/Documents/GitHub/build.bat'
      }
    }
    stage('Test') {
      steps {
        bat 'C:/Users/SQJLCHOO/Documents/GitHub/test.bat'
      }
    }
    stage('Package') {
      steps {
        bat 'C:/Users/SQJLCHOO/Documents/GitHub/package.bat'
      }
    }
        stage('Deploy') {
      steps {
        bat 'C:/Users/SQJLCHOO/Documents/GitHub/deploy.bat'
      }
    }
  }
}
