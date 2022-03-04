pipeline {
    agent any
    stages {
        stage ('Build') {
            steps {
              sh ' echo "this is Build"'
            }
        }
        stage ('test') {
            steps {
              sh '  echo " this is test"'
            }
        }
        stage ('deploy') {
            setps {
              sh 'echo "this is Deploy"'
            }
        }
    }
}