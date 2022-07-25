pipeline {
    agent any
        stages {
            stage('build') {
                steps {
                    sh 'javac main1.java'
                }
            }
            stage('run') {
                steps {
                    sh 'java main1'
                }
            }
        }
}
