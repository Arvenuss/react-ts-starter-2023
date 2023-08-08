pipeline {
  agent any
  tools {nodejs "node"}
  stages {
    stage('npm install version') {
      steps {
        sh 'npm install'
      }
    }
    stage('Install') {
      steps {
        sh 'npm install'
      }
    }
        stages ('Build') {
            steps {
                sh 'npm run build'
            }
        }
      }
    }