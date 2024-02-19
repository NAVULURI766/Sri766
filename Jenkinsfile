pipeline {
    agent any 
stages {
        stage('checking version') {
            steps {
                sh 'mvn --version, '
                
            }
        }
    }
}
node {
  stage ('Build') {
    withMaven(traceability: true) {

    }
  }
}
