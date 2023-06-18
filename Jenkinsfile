/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                echo 'build the application'
            }
        }
        
         stage('test') {
            steps {
                echo 'Test the application'
            }
        }
        
         stage('deploy') {
            steps {
                echo 'Deploy the application'
            }
        }
    }
}
