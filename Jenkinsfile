pipeline {
    agent {
        node {
            label 'maven_slave'
        }
    }
environment {
    PATH = "/opt/apache-maven-3.9.6/bin:$PATH"
}
    stages {
        stage('clone') {
            steps {
                git 'https://github.com/viswkum/ttrend.git'
            }
        }
	stage('build') {
            steps {
                sh 'mvn clean deploy'
            }
        }
    }
}
