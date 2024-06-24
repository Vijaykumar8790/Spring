pipeline {
    agent any
    
    stages {
        
        stage('Test') {
            steps {
                // Replace this with your actual test commands or scripts
                sh 'echo "Running tests..."'
                sh 'mvn test'  // Example: Runs Maven tests, adjust as per your project
            }
        }
    }
    
    post {
        success {
            echo 'Build and Test Success'
            // Additional actions on success can be added here
        }
        failure {
            echo 'Build or Test Failed'
            // Additional actions on failure can be added here
        }
    }
}
