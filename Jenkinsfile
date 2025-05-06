pipeline {
  agent any
  stages {
    stage('Start') {
      parallel {
        stage('Start') {
          steps {
            echo '🚀 Jenkins Pipeline Triggered!'
          }
        }

        stage('') {
          steps {
            git(url: 'https://github.com/Tqhuyen/LoLWinRatePredict.git', branch: 'main')
          }
        }

      }
    }

    stage('Print Info') {
      steps {
        echo '✅ Branch:'
        echo '🕒 Build Number'
        echo '📦 Workspace'
      }
    }

    stage('Test') {
      steps {
        echo 'This is Testing123'
      }
    }

  }
  post {
    always {
      echo '🧼 Done with the pipeline!'
    }

  }
}