pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/opt/maven/apache-maven-3.6.1/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/opt/maven/apache-maven-3.6.1/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "/opt/maven/apache-maven-3.6.1/bin/mvn package"
            }
        }
    }
}
