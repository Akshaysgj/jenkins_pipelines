pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "code is changing"
            }

        }
        stage('Test'){
            steps {
                echo "build with the help of maven"
            }
        }
        stage('Deploy'){
            steps{
                echo "deploy to the applications"
            }
        }
    }
}
