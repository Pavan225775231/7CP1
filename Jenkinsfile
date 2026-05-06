pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build the code using Maven to compile and package the application'
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
                echo 'Analyse code quality using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scan code vulnerabilities using OWASP Dependency Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy the application to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run integration tests on staging using Postman'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy the application to AWS EC2 production server'
            }
        }
    }
}
