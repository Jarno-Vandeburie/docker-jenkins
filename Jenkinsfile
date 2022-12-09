pipeline {
    
    agent{
        label 'Node19.2'
    }
    
    stages {
        stage('Build') {
            steps {
                echo 'this is the build stage'
                node('Node19.2'){
                    sh 'npm init -y' 
                    sh 'npm install -y' 
                }
                
            }
        }
        stage('Test') {
            steps {
                echo 'this is the test stage'
            }
        }
        stage('Deploy') {
            steps {
                echo 'this is the deploy stage'
            }
        }
    }
}
