node{
  stage('clone'){
    git branch: 'master'
    git 'https://github.com/S530485/jenkinsjob2.git'
    git branch: 'feature'
    git 'https://github.com/S530485/jenkinsjob2.git'
    sh 'git add .'
    sh 'git commit -m "feature"'
    sh 'git push origin master'
    git branch: 'master'
    sh 'git merge feature'
  }
  stage('directory'){
    sh 'cd classroom/'
  }
}
