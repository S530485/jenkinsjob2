node{
  stage('clone'){
        properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/60 * * * *')])])
        
  }
  stage('directory'){
    sh 'cd classroom/'
  }
}
