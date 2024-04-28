pipeline {
    agent {
        node {
            label 'maven-agent'
        }
    }

    stages {
        stage('clone code') {
            steps {
                git 'https://github.com/viswkum/ttrend.git'
            }
        }
    }
}
