pipeline {
    agent {label 'demo-docker-slave'}
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
