pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                bat '"C:\\Windows\\System32\\cmd.exe" /c mvn clean'
            }
        }



        stage('Test') {
            steps {
                bat 'mvn test'

            }
        }
        stage('Package') {s
            steps {
                bat 'mvn package'
            }
        }
    }

}
