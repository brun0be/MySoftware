properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -ll'
                sh 'python3 main.py'
            }
        }
    }
}
