#!groovy
properties([disableConcurrentBuilds()])

pipeline{
  agent any
  triggers{pollSCM('* * * * *')}
  stages {
  stage('write') {
    steps {
      echo 'Code was changed and Jenkins saw it!'
    }
  }
}
}
