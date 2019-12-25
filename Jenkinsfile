pipeline {
  agent {
    node {
      label 'jenkins/slave'
    }
  }

    parameters {
        string(name:'TAG_NAME',defaultValue: '',description:'')
    }

    stages {
        stage ('unit test') {
            steps {
                container ('jenkins/slave') {
                    sh 'echo hello'
                }
            }
        }                
    }
}
