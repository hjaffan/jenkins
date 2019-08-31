pipeline {
    agent any
    environment {
        test = "hello"
    }
    stages {
        stage('Inital Stage') {
            steps {
              sh "scripts/hello.sh"
            }
        }
    }
}