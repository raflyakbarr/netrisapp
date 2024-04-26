Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'npm install' 
                archiveArtifacts artifacts: 'project-terbaru.zip', fingerprint: true 
            }
        }
    }
}
