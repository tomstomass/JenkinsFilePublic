pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World from $name $surname'
                git branch: 'main', credentialsId: '300c5936-aadb-40b9-988c-d619338e5d0b', url: 'https://github.com/tomstomass/JenkinsFilePublic.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Realease') {
            steps {
                echo 'Releasing'
            }
        }
    }
}
