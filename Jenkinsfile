pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building'
        echo 'executing Script'
        sh 'scripts/build.sh'
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