pipeline {
    agent {
        docker {
            image 'gradle:4.7.0-jdk8-alpine'
        }
    }
    stages {
        stage('Test') {
                   steps {
                       echo 'Testing'
                       sh 'gradle test'
                   }

        }
    }
}