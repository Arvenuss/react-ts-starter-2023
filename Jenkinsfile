pipeline {
  agent any
  tools {nodejs "node"}
  stages {
    stage('Install') {
      steps {
        sh 'npm install'
        stages ('Build') {
            steps {
                sh 'npm run build'
            }
        }
      }
    }
  }
}