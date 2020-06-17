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
}