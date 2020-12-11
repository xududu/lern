pipeline {
  agent {
    docker {
      image 'nginx'
    }

  }
  stages {
    stage('1') {
      steps {
        sleep 3
      }
    }

    stage('2') {
      steps {
        sh '''echo \'test\'
echo "nginginline" >> /root/log.txt
cat /root/log.txt'''
      }
    }

    stage('') {
      steps {
        input 'abc'
      }
    }

  }
}