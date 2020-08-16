pipeline {
    agent any
    stages {
        stage("check Buildtool Versions") {
            steps {
                sh '''
                echo "Checking versions"
                java -version
                mvn -v
                '''
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