pipeline{
    agent any
    stages{
        stage('Checkout code'){
            steps{
                Checkout scm
            }
        }
        stage('Run extract.py'){
            steps{
                bat 'python extract.py'
            }
        }
    }
}