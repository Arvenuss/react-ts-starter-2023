pipeline {
  agent any
  tools {nodejs "node"}
  stages {
    stage('npm install version') {
      steps {
        sh 'npm install npm@8.19.2 -g'
      }
    }
    // stage('Install') {
    //   steps {
    //     sh 'npm install'
    //   }
    // }
        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }
      }
    }