pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is a sample build, real build is going to be implemented soon...'
            }
        }
        stage('deploy to artifact') {
            steps {
                echo 'Build file will be published to artifactory'
            }
        }
        stage('deploy to dev') {
            steps {
                echo 'Build file will be deployed in dev environment'
            }
        }
          stage('deploy to QA') {
            steps {
                echo 'Build file will be deployed in QA environment'
            }
        }
          stage('deploy to Prod') {
            steps {
                echo 'Build file will be deployed in Prod environment'
            }
        }
    }
}
