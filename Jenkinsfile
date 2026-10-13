pipeline {
    agent any

    stages {
        stage('Récupération du code') {
            steps {
                checkout scm
            }
        }
        stage('Date système') {
            steps {
                sh 'date'
            }
        }
    }
}
