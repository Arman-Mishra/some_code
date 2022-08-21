pipeline {
  agent any
 triggers{
  cron('H/15 * * * *')	
 }
  stages {
    stage('echo') {
      steps {
        sh 'echo "Hello from the Trigger 4"'
      }
    }

  }
}
