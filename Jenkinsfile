pipeline {
    agent any
    stages {
        stage("check Java Version") {
            sh 'java -version'
        }
        stage("Check Maven Version") {
            sh 'mvn -version'
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