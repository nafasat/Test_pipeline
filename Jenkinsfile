pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building'
        echo 'executing Script'
        sh 'scripts/build.sh'
        sh '''cat scripts/build.sh
ls -l scripts/build.sh'''
      }
    }

    stage('Test') {
      steps {
        echo 'testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}