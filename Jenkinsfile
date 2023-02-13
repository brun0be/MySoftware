'properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -lrt'
                sh 'python3 main.py'
            }
        }
    }
}
