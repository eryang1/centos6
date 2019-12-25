pipeline {
  agent {
    node {
      label 'centos'
    }
  }

    parameters {
        string(name:'TAG_NAME',defaultValue: '',description:'')
    }

    stages {
        stage ('unit test') {
            steps {
                container ('centos') {
                    sh 'echo hello'
                }
            }
        }                
    }
}
