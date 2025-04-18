pipeline {
    agent any 
    
    stages {
        // Stage 1
        stage('Build') {
            steps {
                echo "Stage 1: Build"
                echo "Building the code with Maven to compile and package automatically"
                echo "Apache Maven -> Build automation tool for Java"
            }
        }
        
        // Stage 2
        stage('Units and Integrations Tests') {
            steps {
                echo "Stage 2: Units and Integrations Tests"
                echo "Running JUnit for unit testing"
                echo "JUnit -> Unit testing framework for Java"
            }
        }
        
        // Stage 3
        stage('Code Analysis') {
            steps {
                echo "Stage 3: Code Analysis"
                echo "Performing static code analysis, looking for bugs, and bad codes using SonarQube"
                echo "SonarQube -> Static code analysis and identify bugs"
            }
        }
        
        // Stage 4
        stage('Security Scan') {
            steps {
                echo "Stage 4: Security Scan"
                echo "Scanning application dependencies and looking for vulnerabilities with OWASP Dependency-Check"
                echo "OWASP Dependency-Check -> Detect any known vulnerabilities within components"
            }
        }
        
        // Stage 5
        stage('Deploy to Staging') {
            steps {
                echo "Stage 5: Deploy to Staging"
                echo "Deploying the application to staging using AWS CLI"
                echo "AWS CLI -> Command Line Interface tool for deploy to AWS EC2 instances"
            }
        }
        
        // Stage 6
        stage('Integration Tests on Staging') {
            steps {
                echo "Stage 6: Integration Tests on Staging"
                echo "Running Postman integration tests in staging environment"
                echo "Postman -> API testing tools"            
            }
        }
        
        // Stage 7
        stage('Deploy to Production') {
            steps {
                echo "Stage 7: Deploy to Production"
                echo "Using AWS CodeDeploy to deploy the application to production"
                echo "AWS CodeDeploy -> Automates application deployment to EC2 instances"  
            }
        }
    }
}
