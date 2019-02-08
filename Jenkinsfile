node{
  stage('clone'){
checkout([$class: 'GitSCM', branches: [[name: '*/master']], browser: [$class: 'GithubWeb', repoUrl: 'https://github.com/S530485/jenkinsjob2.git'], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '4bfd197f-e194-45da-aa0f-a3ef907324ac', url: 'https://github.com/S530485/jenkinsjob2.git']]])  }
  stage('directory'){
    sh 'cd classroom/'
  }
}
