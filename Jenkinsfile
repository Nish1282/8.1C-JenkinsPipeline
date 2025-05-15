pipeline {
    agent any

    stages {
        stage("Build") {
            steps {
                bat "echo Using Maven to build the code"
            }
        }

        stage("Unit and Integration Tests") {
            steps {
                bat "echo Using JUnit to run unit and integration tests"
            }
        }

        stage("Code Analysis") {
            steps {
                bat "echo Using SonarQube for code analysis"
            }
        }

        stage("Security Scan") {
            steps {
                bat "echo Using OWASP Dependency-Check for security scanning"
            }
        }

        stage("Deploy to Staging") {
            steps {
                bat "echo Deploying to AWS EC2 staging server"
            }
        }

        stage("Integration Tests on Staging") {
            steps {
                bat "echo Using Selenium for integration testing on staging"
            }
        }

        stage("Deploy to Production") {
            steps {
                bat "echo Deploying to AWS EC2 production server"
            }
        }
    }
}
