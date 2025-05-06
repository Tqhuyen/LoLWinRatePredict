pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        echo '🚀 Jenkins Pipeline Triggered!'
      }
    }

    stage('Print Info') {
      steps {
        echo "✅ Branch: ${env.BRANCH_NAME}"
        echo "🕒 Build Number: ${env.BUILD_NUMBER}"
        echo "📦 Workspace: ${env.WORKSPACE}"
      }
    }

  }
  post {
    always {
      echo '🧼 Done with the pipeline!'
    }

  }
}