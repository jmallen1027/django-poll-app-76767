pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'pip install -r requirements.txt' 
            }
        }
        stage('Test') { 
            steps {
                echo 'python3 manage.py test' 
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo deploying' 
            }
        }
    }
}
