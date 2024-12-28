pipeline {
    agent any

    stages {
        // Build Stage
        stage('Build') {
            steps {
                // Uncomment the line below for Windows
                bat 'gradlew.bat assemble'
                // Comment out or remove the line below for Windows
                // sh './gradlew assemble'
            }
        }

        // Test Stage
        stage('Test') {
            steps {
                // Uncomment the line below for Windows
                bat 'gradlew.bat test'
                // Comment out or remove the line below for Windows
                // sh './gradlew test'
            }
        }
    }
}

