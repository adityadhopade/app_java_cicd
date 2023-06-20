@Library('my-shared-library') _

pipeline {
    agent any 
    stages {
        stage('Git checkout') {
            steps {
                gitCheckout(
                    branch: "main",
                    url: "https://github.com/adityadhopade/app_java_cicd.git"     
                )
            }
        }
    }
}