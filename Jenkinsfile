pipeline {
  agent {
    label 'linux'
  }
  options {
    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: 'S', daysToKeepStr: '', numToKeepStr: 'S')
    disableConcurrentBuilds()
  }
  stages {
    stage('Hello') {
      steps {
        echo "hello"
      }
    }
  }
}
