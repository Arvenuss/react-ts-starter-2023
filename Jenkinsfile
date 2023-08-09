pipeline {
  agent any
  tools {nodejs "node"}
  stages {
    stage('set npm version') {
      steps {
        sh 'npm install npm@8.19.2 -g'
      }
    }
    stage('npm install') {
      steps {
        sh 'npm install'
      }
    }
        stage('npm build') {
            steps {
                sh 'npm run build'
            }
        }
      }
    }