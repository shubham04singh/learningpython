pipeline {
    agent any
    stages {
         stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/shubham04singh/learningpython.git'
            }
        }
        stage ('setup'){
            steps{
                echo 'setting up environment'
                sh 'pyhton --version'
            }
        }
    stage ('test python script')
    {
        steps{
            echo 'running python script '
            sh 'python hello.py'
        }
    }
    }
}
