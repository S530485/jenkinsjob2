node{
  stage('clone'){
    git branch: 'master'
    git 'https://github.com/S530485/jenkinsjob2.git'
    git branch: 'feature'
    git 'https://github.com/S530485/jenkinsjob2.git'
    sh 'git push origin master'
  }
  stage('directory'){
    sh 'cd classroom/'
  }
}
