pipeline {
    agent any

    stages {
        stage('Checkout code') {
            steps {
                checkout scm
            }
        }

        stage('Run extract.py') {
            steps {
                bat 'C:\\Users\\Win11\\AppData\\Local\\Programs\\Python\\Python313\\python.exe extract.py'
            }
        }
    }
}
