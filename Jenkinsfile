pipeline {
    agent any
    stages {
      stage('Install dependencies'){
        steps {
          echo ("start install")
          // sh("npm install")
          // echo ("end install")
        }
      stages {
        stage('Test Script'){
          steps {
            echo ("start script")
            script {
              for (int i = 0; i < 5; i++)
              echo ("Script ${i}")
            }
          }
        }
      }
      }
    }
}