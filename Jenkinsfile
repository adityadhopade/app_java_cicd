@Library('my-shared-library') _

pipeline {
    agent any 
    stages {
        stage('Git Checkout') {
            steps {
                gitCheckout(
                    branch: "main",
                    url: "https://github.com/adityadhopade/app_java_cicd.git"     
                )
            }
        }
    }
}