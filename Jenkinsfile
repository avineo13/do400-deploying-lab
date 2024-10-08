pipeline {

    agent {
        node {
            label 'maven'
        }
    }

    stages {

        stage('Test') {
            sh './mvnw verify'
        }

    }
}