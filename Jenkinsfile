node{
  stage('clone'){
    git branch: 'master'
    git 'https://github.com/S530485/jenkinsjob2.git'
    git branch: 'feature'
    git 'https://github.com/S530485/jenkinsjob2.git'
    sh 'touch abc'
    sh 'git config --global user.name "S530485"'
    sh 'git config --global user.email ravipati0102@gmail.com'
    sh 'git add .'
    sh 'git commit -m "feature"'
    sh 'git push origin feature'
    git branch: 'master'
    sh 'git merge feature'
  }
  stage('directory'){
    sh 'cd classroom/'
  }
}
