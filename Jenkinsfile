pipeline {
    agent any
    stages {
        stage("check Java Version") {
            steps {
                sh 'java -version'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}