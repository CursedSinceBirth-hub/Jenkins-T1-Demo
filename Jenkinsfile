pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/CursedSinceBirth-hub/Jenkins-T1-Demo.git'
            }
        }

        stage('Compile') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}
