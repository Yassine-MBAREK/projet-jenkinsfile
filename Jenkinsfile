pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'gcc hello.c -o hello'
            }
        }
    }
}
