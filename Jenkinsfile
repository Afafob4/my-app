pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                bat script: 'mvn clean', tool: 'Maven'
            }
        }


        stage('Test') {
            steps {
                bat 'mvn test'

            }
        }
        stage('Package') {
            steps {
                bat 'mvn package'
            }
        }
    }

}
