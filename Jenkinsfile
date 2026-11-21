pipeline {
    agent any

    stages {
        stage('Checkout Git') {
            steps {
                git branch: 'main', url: 'https://github.com/Oussema166/oussema-mhamdi.git'
            }
        }

        stage('Build Maven') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
