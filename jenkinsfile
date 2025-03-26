pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "python test.py"
            }
        }
        stage('Test') { 
            steps {
            echo "stage-2"
            }
        }
        stage('Deploy') { 
            steps {
                echo "stage-3"
            }
        }
    }
}
