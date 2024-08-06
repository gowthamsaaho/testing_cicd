pipeline {
    agent any
    tools{
        jdk 'java17'
        maven 'maven3'
    }
    stages {
        stage('Git checkout') {
            steps {
                git changelog: false, poll: false, url: 'https://github.com/gowthamsaaho/testing_cicd.git'
            }
        }
    }
}

