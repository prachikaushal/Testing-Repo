pipeline {
  agent any
  stages {
    stage('Git checkout') {
      steps {
        git 'https://github.com/prachikaushal/Testing-Repo.git'
        git(url: 'https://github.com/prachikaushal/Testing-Repo.git', branch: 'master')
      }
    }

  }
}