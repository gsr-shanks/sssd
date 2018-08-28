pipeline {
    triggers {
            issueCommentTrigger('.*test this please.*')
        }
  agent {
    node {
      label 'sssd-ci-slave'
    }

  }
  stages {
    stage('build') {
      steps {
        sh '''env
        ls
        pwd'''

      }
    }
  }
}