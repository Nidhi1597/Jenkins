pipeline {
    agent {
        docker { image 'jenkins' }
    }
    stages {
        stage('Build') {
            steps {
                sh 'gradle clean build'
            }
        }
    }
    stages {
            stage('Test') {
                steps {
                    sh './gradlew test'
                }
            }
        }
}