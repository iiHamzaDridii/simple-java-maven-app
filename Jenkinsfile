

pipeline {
    agent any
    tools {
        maven 'Maven 3.9.2' // Name of the Maven installation configured in Jenkins
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
