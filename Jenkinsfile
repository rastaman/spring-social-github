pipeline {
    agent { docker 'gradle:4.2.1-jdk8' }
    stages {
        stage('build') {
            steps {
                sh './gradlew build assemble distZip'
            }
        }
    }
}