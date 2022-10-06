@Library('robot-shared-library@main') _
pipeline{
    agent any
    stages {
        stage('Installing the node js dependencies') {
            steps {
                sh "npm install"
            }
        }
        stage('Lint checks') {
            steps {
                script {
                    sample.info("Welcome","stockexcnage.com")
                }
                sh "echo installing jslint"
               //  sh "npm i jslint"
                // sh "~/node_modules/jslint/bin/jslint.js server.js"
                sh "lint checks completed"
            }

        }
    }
}