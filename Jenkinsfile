pipeline {
    agent any
    stages {
        stage ('setup'{
            steps{
                echo 'setting up environment'
                sh 'pyhton --version'
            }
        })
    stage ('test python script')
    {
        steps{
            echo 'running python script '
            sh 'python hello.py'
        }
    }
    }
}