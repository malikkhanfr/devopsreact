pipeline {
    agent {
        docker {
            image 'node:lts-buster-slim' 
            args '-p 3000:3000' 
        }
         environment {
        HOME = '.'
    }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm installlll' 
            }
        }
    }
}
