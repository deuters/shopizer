pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/deuters/shopizer.git'
                sh './mvnw clean clean compile'
            }
        }
    }
}
