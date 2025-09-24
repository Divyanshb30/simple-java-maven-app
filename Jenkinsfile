pipeline {
    agent any

    tools {
        // This must match the name you gave the Maven installation in Jenkins
        maven 'M3' 
    }

    stages {
        stage('Build') {
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}
