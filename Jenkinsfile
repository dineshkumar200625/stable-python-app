pipeline {
    agent any
    stages {
        stage('Deploy Stable App') {
            steps {
                // Using the verified path to your kubectl binary
                sh 'kubectl apply -f stable-app.yaml'
            }
        }
    }
}
