pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo "Hello from Organization 2 Jenkinsfile - I am from ${env.BRANCH_NAME}"
      }
    }

    stage('Hello Again') {
      steps {
        echo "The build Id was: ${BUILD_ID}"
      }
    }

    stage('Bye Now') {
      steps {
        echo "Jenkins Agent for this build was: ${JENKINS_AGENT_NAME}"
        echo "Git commit hash: ${GIT_COMMIT}"
      }
    }
  }
}
