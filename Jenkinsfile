pipeline {
    agent any

    stages {
        stage('validate') {
            steps {
                echo 'validating..'
                sh 'pwd'
                sh 'mvn compile'      
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
