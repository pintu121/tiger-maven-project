pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main', url: 'https://github.com/pintu121/tiger-maven-project.git'
            }
        }
    }
}
