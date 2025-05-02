pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/joke070/CI-CD-PIPELINE-PROJECT-WITH-JENKINS.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
                sh 'npm install pm2' // ✅ install pm2 locally
            }
        }

        stage('Run App') {
            steps {
                sh 'npx pm2 delete all || true'     // ✅ run pm2 from node_modules
                sh 'npx pm2 start index.js'
            }
        }
    }
}