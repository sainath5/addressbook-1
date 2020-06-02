pipeline {
    agent any
    stages {
        stage('Compileing') {
            steps {
                sh '/usr/local/src/apache-maven/bin/mvn compile'
            }
        }
        stage('Testing') {
            steps {
                sh '/usr/local/src/apache-maven/bin/mvn test'
            }
        }
        stage('Packaging') {
            steps {
                sh '/usr/local/src/apache-maven/bin/mvn package'
                
            }
        }
    }
}
