pipeline {
    agent any
    stages {
        stage("check Buildtool Versions") {
            steps {
                sh '''
                java -version
                mvn -v
                gradle -v
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