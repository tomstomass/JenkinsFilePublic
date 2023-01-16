pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World from Toms Freimanis'
                git branch: 'main', credentialsId: '300c5936-aadb-40b9-988c-d619338e5d0b', url: 'https://github.com/tomstomass/JenkinsFilePublic.git'
            }
        }
    }
}
