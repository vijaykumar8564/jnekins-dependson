pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Commands to build your project
                echo 'Building the project...'
            }
        }
        
        stage('Test') {
            steps {
                // Commands to run tests
                echo 'Running tests...'
            }
        }
        
        stage('Deploy') {
            dependsOn 'Test'
            steps {
                // Commands to deploy the application
                echo 'Deployining after the test completion only'
            }
        }
    }
}
