pipeline {
    agent any
    stages {
        stage('Git Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage('Starting minikube') {
            steps {
                sh '''/usr/local/bin/minikube start
                      kubectl get pods'''
            }
        }
    }
}

