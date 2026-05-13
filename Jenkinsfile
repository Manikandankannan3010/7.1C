pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Stage: Compiling and packaging the code using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Testing Stage: Running unit tests using JUnit and integration tests using Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Code Analysis Stage: Checking code quality using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security Scan Stage: Scanning vulnerabilities using OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy Stage: Deploying application to staging server using AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Staging Test Stage: Running tests on staging using Postman and Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Production Stage: Deploying final application to production server using AWS EC2'
            }
        } 
    }
    }

