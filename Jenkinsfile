pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        echo 'Checkout'
      }
    }
    stage('Build') {
      steps {
        sleep 3
        echo 'Building'
        sleep 4
      }
    }
    stage('Run Unit Tests') {
      steps {
        sleep 10
        echo 'Unit Tests Pass'
      }
    }
    stage('Run UI Tests') {
      steps {
        sleep 4
        echo 'Running UI Tests'
      }
    }
    stage('Tag') {
      steps {
        echo 'Tagging Build'
      }
    }
  }
}