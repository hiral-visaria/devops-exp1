pipeline {
  agent any
  
  stages {
    stage("Build") {
      steps  {
        sh 'cd /var/www/html/'
        sh 'sudo rm -rf devops-exp1'
        sh 'sudo git clone https://github.com/hiral-visaria/devops-exp1'
      }
    }
  }
}
