@Library('my-shared-library') _
pipeline {
    agent any

    stages {
        stage('Git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/SamipDave/java-app-cicd-shared-library.git'
            }
        }
    }
}
