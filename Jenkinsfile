pipeline {
    agent any
    stages {
        stage('Deploy Stable App') {
            steps {
                // Using the verified path to your kubectl binary
                sh '/var/jenkins_home/bin/kubectl apply -f stable-app.yaml'
            }
        }
    }
}
