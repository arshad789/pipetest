pipeline{
    agent any
    stage('Build') {
        step{
            sh 'sleep4'

        }
    }
    stage('test') {
        step{
            sh '''
            sleep5
            echo "this is Test test1"
            '''

        }
    }
    stage('Deploy'){
        step{
            sh '''
            echo "this is Deploy test"
            '''
        
        }
    }
    stage('test stage'){
        step{
            sh ' echo "tesing" '
        }
    }
    

    clear
