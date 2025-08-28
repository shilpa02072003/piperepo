pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Hello build stage'
            }
        }
        stage ("test"){
            steps {
                echo "Hello test"
                sh 'ls'
            }
        }
