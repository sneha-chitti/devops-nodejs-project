pipeline {
    agent any

    tools {
        nodejs 'nodejs'
    }

    stages {

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run Application') {
            steps {
                bat 'node app.js'
            }
        }

    }
}
