pipeline {
    agent any
    stages {
        stage('Deploy to main') {
            when {
                branch 'main'
            }
            steps {
                echo 'Deploying to main environment...'
            }
        }
        stage('Deploy to QA') {
            when {
                branch 'QA'
            }
            steps {
                echo 'Deploying to QA environment...'
            }
        }
        stage('Deploy to Preprod') {
            when {
                branch 'Preprod'
            }
            steps {
                echo 'Deploying to Preprod environment...'
            }
        }
        stage('Deploy to Prod') {
            when {
                branch 'Prod'
            }
            steps {
                echo 'Deploying to Prod environment...'
            }
        }
    }
}
