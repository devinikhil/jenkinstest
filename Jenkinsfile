pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/devinikhil/jenkinstest.git'
            }
        }
        
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
