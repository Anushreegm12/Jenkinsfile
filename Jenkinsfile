pipeline {
  agent any
  stages {
    stage('Clone Repository') {
      steps {
        git url:'https://github.com/Anushreegm12/Jenkinsfile.git',branch:'main'
      }
    }
    stage('Build') {
      steps {
        sh 'echo "Building the application...."'
      }
    }
    stage('test') {
      steps {
        sh 'echo "Running tests...."'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "Deploying application...."'
      }
    }
  }
}
