pipeline {
      agent any

      stages {
          stage('Build-Stage 1') {
              steps {
                  echo "Start of Build"
                  echo "Building....."
                  sh'''
                  echo "command 1"
                  pwd
                  ls -la
                  '''
                  echo "Hello Jenkins"
                  echo "End of Stage build"
              }
          }
          stage('Test-Stage 2') {
              steps {
                  echo "Start of Test"
                  echo "Testing....."
                  echo "End of Stage build"
              }
          }
          stage('Deployment-Stage 3') {
              steps {
                  echo "Start of Deployment"
                  echo "Deploying....."
                  echo "End of Stage build"
              }    
          }
      }
}
