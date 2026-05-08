pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build the code using Maven build automation tool'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Run unit tests using JUnit'
                echo 'Run integration tests using Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyse code using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Perform security scan using Snyk'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy application to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run staging integration tests using Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy application to AWS EC2 production server'
            }
        }
    }
}
