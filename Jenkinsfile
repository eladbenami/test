pipeline {
  agent any
  stages {
    stage('pre-build') {
      steps {
        echo 'pre build step'
      }
    }
    stage('') {
      steps {
        mail(subject: 'test', body: 'sfss', from: 'elad.benami@gmail.com', to: 'elad.benami@gmail.com')
      }
    }
  }
}