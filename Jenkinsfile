#!/usr/bin/env groovy
pipeline {
    agent any
    stages {
        stage('拉取代码') {
            steps {
                echo 'Pull code'
            }
        }
        stage ('代码扫描') {
            steps {
                echo 'sonarqube'
            }
        }
    }
}
