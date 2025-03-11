pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage ('clean'){
        steps {
            sh 'mvn clean'
        }
        }
        stage ('validate') {
        steps {
            sh 'mvn validate'
        }
        }
        stage ('compile') {
        steps {
            sh 'mvn compile'
        }
        }
        stage ('package') {
        steps {
            sh 'mvn package'
        }
        }
        }
}