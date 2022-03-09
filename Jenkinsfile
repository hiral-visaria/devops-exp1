pipeline {
  agent any
  
  stages {
    stage("Hello") {
      steps  {
        cd /var/www
        git pull origin master
      }
    }
  }
}
