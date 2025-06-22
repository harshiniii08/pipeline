pipeline {
    agent any
    stages {
        stage('Job1: GitHub Access') {
            steps {
                build job: 'Job1'
            }
        }
        stage('Job2: Java Program Execution') {
            steps {
                build job: 'Job2'
            }
        }
        stage('Job3: Python Program Execution') {
            steps {
                build job: 'Job3'
            }
        }
    }
}
