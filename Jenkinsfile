pipeline {
  agent any
  stages {
    stage('Upload to AWS.'){
      steps {
        sh 'echo "Hello World"'
        sh '''
          echo "Multiline steps works too"
          ls -lah
        '''
      }
    }
  }
}
