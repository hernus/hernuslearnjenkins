pipeline {
    agent any

    stages {
        stage('Step 1') {
            steps {
                sh 'sleep 3' 
                echo 'hello1'
            }
        }
        stage('Step 2') {
            steps {
                sh 'sleep 3' 
                echo 'hello2'
            }
        }
        stage('Other job') {
            steps {
                build job: 'hello1'
            }
        }

    }
}