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
                echo "✅ Branch:"
                echo "🕒 Build Number"
                echo "📦 Workspace"
            }
        }
    }

    post {
        always {
            echo '🧼 Done with the pipeline!'
        }
    }
}