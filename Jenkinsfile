pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('List') {
            steps {
              sh '''
              //https://github.com/collinsefe/jenkins-pipeline.git
              ls -la
              '''
                }
            }
        stage('Timer') {
            steps {
              sh 'sleep 10'
                }
            }
    }
}
