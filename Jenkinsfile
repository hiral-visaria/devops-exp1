pipeline {
  agent any
  
  stages {
    stage("Build") {
      steps  {
        sh 'cd /var/www/html/devops-exp1'
        sh 'git pull origin master'
      }
    }
    stage("Deploy") {
      steps  {
        sh 'cd /var/www/html/devops-exp1'
        sh 'git pull origin master'
      }
    }
  }
}
