pipeline {
    agent { docker { image 'maven:3.6.0' } }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}