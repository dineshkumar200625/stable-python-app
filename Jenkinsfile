pipeline {
    agent { label 'built-in' }
    stages {
        stage('Deploy Stable App') {
            steps {
                // Using the verified path to your kubectl binary
                
                sh '/tmp/kubectl apply -f stable-app.yaml'
            }
        }
    }
}
