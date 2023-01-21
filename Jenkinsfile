pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                sh 'mvn package'
            }
        }
        stage('Deploy') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
