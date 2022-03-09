pipeline {
  agent any
  
  stages {
    stage("Build") {
      steps  {
        sh 'cd /var/www/html/'
        sh 'rm -rf devops-exp1'
        sh 'git clone https://github.com/hiral-visaria/devops-exp1'
      }
    }
  }
}
