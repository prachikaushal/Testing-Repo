pipeline {
  agent any
  stages {
    stage('Git checkout') {
      steps {
        git(url: 'https://github.com/prachikaushal/Testing-Repo.git', branch: 'master')
        echo 'Successfully Checked out'
      }
    }

    stage('Compile') {
      steps {
        bat 'Compile.bat'
        echo 'Compiled Successfully'
      }
    }

    stage('Package') {
      steps {
        bat 'Package.bat'
        echo 'Packaged successfully'
      }
    }

    stage('Deploy') {
      steps {
        bat 'Deploy.bat'
        echo 'Deployed successfully'
      }
    }

  }
}