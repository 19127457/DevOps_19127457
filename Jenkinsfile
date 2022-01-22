pipeline {
    agent any
  stages {
    stage('Clone') {
      steps {
        git 'https://github.com/19127457/DevOps_19127457'
      }
    }
  stage('Build') {
      steps {
       	withDockerRegistry)credenttialsId: 'docker-hub', url: 'https://github.com/19127457/DevOps_19127457'
	sh 'docker build -t 19127457/nodejs-test:v10'
	sh 'docker push 19127457/nodejs-test:v10'
      }
  }
}
