pipeline {
  agent {
    node {
      label 'maven'
    }
  }

    parameters {
        string(name:'TAG_NAME',defaultValue: '',description:'')
    }

    stages {
        stage ('unit test') {
            steps {
                container ('maven') {
                    sh 'echo hello'
                }
            }
        }                
    }
}
