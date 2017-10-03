pipeline {
  agent any
  stages {
    stage('Get Rid of Your Stuff') {
      steps {
            sh 'echo "Hello World"'
            sh '''
                echo "Multiline shell steps works too"
                ls -lah
            '''
      }
    }
  }
}