#!/usr/bin/env groovy

pipeline {

    agent {
        docker {
            image 'node:8'
            args '-u root'
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm install'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }    
    }
}
