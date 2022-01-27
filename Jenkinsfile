pipeline {
    agent any
    stages {
        
        stage('Hello') {
            steps {
                echo 'Hello Print Message'
            }
        }
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                //git 'https://github.com/collinsefe/jenkins-pipeline.git'
                aws -version

                // Run shell script
                sh "ls -la"

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }

        }
        
        stage('Timer') {
            steps {
              sh 'sleep 10'
                }
            }
    }
}
