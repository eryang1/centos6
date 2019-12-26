pipeline {
  agent {
    node {
      label 'base'
    }
  }

    parameters {
        string(name:'TAG_NAME',defaultValue: '',description:'')
    }

    stages {
        stage ('unit test1') {
            steps {
                container ('base') {
                    sh 'echo hello'
                }
            }
        } 
        stage ('unit test2') {
            steps {
                container ('base') {
                    sh 'echo 111 > /mnt/ey/test1'
                }
            }
        }     
        stage ('unit test3') {
            steps {
                container ('base') {
                    sh 'echo 222 > /mnt/ey/test2'
                }
            }
        }     
        stage ('unit test4') {
            steps {
                container ('base') {
                    sh 'sleep 10'
                }
            }
        }     
    }
}
