#!/usr/bin/env groovy

node{
  stage('clone'){
        properties([pipelineTriggers([[$class: 'GitHubPushTrigger'], pollSCM('H/60 * * * *')])])
        checkout scm
  }
  stage('directory'){
    sh 'cd classroom/'
  }
}
