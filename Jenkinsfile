pipeline {
  agent any
  options {
    ansiColor('xterm')
    timestamps()
    timeout(time: 1, unit: 'HOURS')
  }
  stages {
    stage("Repository") {
      steps {
          //git url: "https://github.com/mario21ic/jenkins-pipeline.git"
        checkout scm
      }
    }
    stage("Build") {
      steps {
        echo "build"
        sh "echo ${env.BUILD_NUMBER}"
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
