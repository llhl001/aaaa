pipeline {
    agent any
    stages {
        stage('Example'){
            steps {
            echo 'Hello world'
            }
        }
        stage('Example1'){
            steps {
            echo 'Hello1 world'
            }
        }
    }
    post {
        always {
            echo 'say goodbay'
        }
    }
}
