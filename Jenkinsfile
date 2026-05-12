pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                checkout scm
            }
        }

        stage('list files') {
            steps {
                bat 'dir'
            }
        }

        stage('webhook') {
            steps {
                echo 'ajout webhook'
            }
        }

    }
}