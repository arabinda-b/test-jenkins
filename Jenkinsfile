pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                pwd
                ls
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }

    post {
        success {
            echo "Build is successful."
        }
        failure {
            echo "Build failed."
        }
    }
}
