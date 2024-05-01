pipeline {
    agent {
        node {
            label 'maven_slave'
        }
    }
    stages {
        stage('clone') {
            steps {
                git 'https://github.com/viswkum/ttrend.git'
            }
        }
    }
}


