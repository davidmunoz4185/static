pipeline {
  agent any
  stages {
    stage('Upload to AWS.'){
      steps {
        withAWS(region:'eu-west-1',credentials:'aws-static') {
              s3Upload(bucket: 'dmm-p4', workingDir:'.', includePathPattern:'*.html');
        }
      }
    }
  }
}
