pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'testing'
        sh '''cat scripts/build.sh
chmod +x scripts/build.sh
ls -l scripts/build.sh
scripts/build.sh'''
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}