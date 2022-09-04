#!groovy
properties([disableConcurrentBuilds()])

pipeline{
  agent any
  triggers{pollSCM('* * * * *')}
  stages {
  stage('install') {
    steps {
      echo 'Code was changed and Jenkins saw it!'
    }
  }

}
  
}
