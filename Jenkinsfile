@Library('jenkins-shared-library@main') _

pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                gitCheckout(
                    branch: "main",
                    url: "https://github.com/kelvinduan2020/jenkins-shared-library.git"
                )
            }
        }
        stage ('Example') {
            steps {
                // log.info 'Starting' 
                script { 
                    log.info 'Starting'
                    log.warning 'Nothing to do!'
                }
            }
        }
    }
}
