node{
  stage('clone'){
        properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/60 * * * *')])])
        checkout SCM
  }
  stage('directory'){
    sh 'cd classroom/'
  }
}
