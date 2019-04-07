pipeline {
  agent {
    docker {
      image 'howardjones/fpm-rpm-builder:latest'
      args '--uid 0:0'
    }

  }
  stages {

    stage('Test') {
      steps {
        echo 'This is a test'
      }
    }

  }
}
