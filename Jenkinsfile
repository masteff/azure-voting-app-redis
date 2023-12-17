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
        pwsh(script: 'docker compose build')
      }
    }

  }
}
