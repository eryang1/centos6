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
        stage ('unit test'1) {
            steps {
                container ('maven') {
                    sh 'echo 'test1' > /tmp/test1'
                }
            }
        }                
    }
	
	stages {
        stage ('unit test2') {
            steps {
                container ('maven') {
                    sh 'echo 'test2' > /tmp/test2'
                }
            }
        }                
    }
	
	stages {
        stage ('unit test3') {
            steps {
                container ('maven') {
                    sh 'echo 'test3' > /tmp/test3'
                }
            }
        }                
    }
	
	stages {
        stage ('unit test4') {
            steps {
                container ('maven') {
                    sh 'sleep 600'
                }
            }
        }                
    }
}
