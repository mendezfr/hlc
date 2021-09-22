pipeline {
  agent any
  stages {
    stage('3') {
      steps {
        echo 'hola'
      }
    }

    stage('4') {
      steps {
        git(url: 'https://github.com/mendezfr/hlc.git', branch: 'scripting')
      }
    }

  }
}