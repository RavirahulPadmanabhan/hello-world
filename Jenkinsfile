pipeline {
  agent {
    node {
      label 'node_label'
    }

  }
  stages {
    stage('') {
      steps {
        git(url: 'https://github.com/RavirahulPadmanabhan/hello-world', branch: 'master', poll: true)
      }
    }

  }
  environment {
    key1 = 'val1'
  }
}