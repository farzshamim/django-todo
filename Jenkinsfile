pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/farzshamim/django-todo', branch: 'develop')
      }
    }

  }
}