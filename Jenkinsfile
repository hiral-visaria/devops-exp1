pipeline {
  agent any
  
  stages {
    stage("Build") {
      steps  {
        sh 'cd /var/www'
        sh 'git pull origin master'
      }
    }
  }
}
