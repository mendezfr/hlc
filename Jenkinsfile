pipeline {
  agent any
  stages {
    stage('2') {
      steps {
        script {
          pipeline {
            agent any

            stages {
              stage('Hello') {
                steps {
                  echo 'Hello World'
                }
              }
            }
          }
        }

      }
    }

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