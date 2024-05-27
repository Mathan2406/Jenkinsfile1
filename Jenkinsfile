pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/Mathan2406/Jenkinsfile1.git', branch: 'main'
            }
        }
        stage('Load Jenkinsfile') {
            steps {
                script {
                    load 'Jenkinsfile1'
                }
            }
        }
    }
}
