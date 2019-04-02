pipeline {
  agent {
    node {
      label 'Sher'
    }

  }
  stages {
    stage('Sher\'s Stage') {
      steps {
        build(job: 'DevOps', propagate: true, quietPeriod: -3, wait: true)
      }
    }
  }
  environment {
    Sher = 'High'
  }
}