pipeline {
  agent any

  stages {
    stage('Verifiy Branch') {
      steps{
        echo "$GIT_BRANCH"
      }
    }
    stage('Docker Build'){
      steps{
        sh(script: 'docker compose build')
      }
    }

  }
}
