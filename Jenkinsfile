pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/filz0r/astro-api', branch: 'main', changelog: true)
      }
    }

  }
}