pipeline {
    agent {label 'demo-docker-slave'}
            args '-v /root/.m2:/root/.m2'
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package
            }
        }
    }
}