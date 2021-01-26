@Library('piper-lib-os') _

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                mtaBuild script: this
            }
        }
    }
}