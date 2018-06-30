pipeline {
  agent any
  stages {
    stage("Repository") {
      steps {
        echo "repository"
      }
    }
    stage("Build") {
      steps {
        echo "build"
      }
    }
    stage("Test") {
      steps {
        sh "echo tests"
      }
    }
    stage("Deploy") {
      steps {
        sh "echo deploy"
      }
    }
  } 
}
