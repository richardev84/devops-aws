pipeline {
    agent any

    stages {
        stage('Clone-Repo') {
                steps {
                        checkout scm
                }
        }
        stage('Build') {
                steps {
                        sh 'mvn install'
                }
        }
        
    }
}
