pipeline {
  agent {
    node {
      label 'alyuan/centos6.5'
    }
  }

    parameters {
        string(name:'TAG_NAME',defaultValue: '',description:'')
    }

    stages {
        stage ('unit test'1) {
            steps {
                container ('alyuan/centos6.5') {
                    sh 'echo 'test1' > /tmp/test1'
                }
            }
        }                
    }
	
	stages {
        stage ('unit test2') {
            steps {
                container ('alyuan/centos6.5') {
                    sh 'echo 'test2' > /tmp/test2'
                }
            }
        }                
    }
	
	stages {
        stage ('unit test3') {
            steps {
                container ('alyuan/centos6.5') {
                    sh 'echo 'test3' > /tmp/test3'
                }
            }
        }                
    }
	
	stages {
        stage ('unit test4') {
            steps {
                container ('alyuan/centos6.5') {
                    sh 'sleep 600'
                }
            }
        }                
    }
}
