#!groovy

node {

  step([$class: 'WsCleanup'])

  stage "Checkout Git repo"
    checkout scm
  stage "Little Test"
    sh "echo hello world"

}