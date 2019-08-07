pipeline {
  agent any 
  stages {
    stage('Upload to AWS.') {
      steps {
        sh 'echo "hello world"'
        sh '''
          echo "Multiline shell steps works too"
          ls -lah 
        '''  
      }
    }
  }
}
