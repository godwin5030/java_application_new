pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'mvn package'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo "Test step"'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo "Deploy step"'
            }
        }
    }
}
