pipeline {
    agent any

    stages {
        stage('verifyPerformance') {
            steps {
                bat "mvn verify -Pperformance"
            }
        }

    }
}