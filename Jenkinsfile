pipeline {
  agent any
  stages {
    stage('Upload to AWS') {
        withAWS(region:'us-west-2'){
          s3Upload(file:'index.html', bucket:'jenkinspipelineproject3')
        }
      }
    }
  }
}
