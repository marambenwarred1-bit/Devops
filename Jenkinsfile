pipeline {
    agent any

    stages {
        stage('Checkout Git') {
            steps {
                git branch: 'main', url: 'https://github.com/marambenwarred1-bit/devops.git'
            }
        }

        stage('Build Maven') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
