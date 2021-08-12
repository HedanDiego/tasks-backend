pipeline {
    agent any
    stages {
        stage ('Build Backend') {
            steps {
                bat 'mvn clean package -DskipTests=True'

            }
        }
        stage ('Unit Test') {
            steps {
                bat 'mvn test'
            }
    }
    }
}