pipeline {
  agent any
  triggers {
    eventTrigger simpleMatch('Happify')
  }
  stages {
    stage('Received Happify') {
      steps {
        echo 'Received a Happify event'
      }
    }
  }
}
